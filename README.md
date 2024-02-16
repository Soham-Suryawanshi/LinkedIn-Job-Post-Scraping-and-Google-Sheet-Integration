# LinkedIn-Job-Post-Scraping-and-Google-Sheet-Integration

Part 1: Web Scraping LinkedIn
Used Python and BeautifulSoup, Selenium web scraping libraries to extract job posts from LinkedIn.
Filtered jobs based on the following criteria:
● Job Location: England (Can be changed as desired)
● Job Type: Full-time and Contract
● Work Format: Remote
Extracted Information:
● Company Name
● Job Title
● Job Location
● Salary
● Job Post URL

Part 2: Google Sheet Integration
Synced with Google Sheet:
Used the gspread library to sync the extracted job post information with a Google
Sheet.
Each run's unique output is appended to the old extracted output in the
Google Sheet.
