# Russian_Casualties_In_Ukraine_War
Python web scraper for extract russian military casualties in ukraine war
📊 Minfin (Ukraine War) Casualties Analysis
The goal of this project is to scrape daily military casualty data from the open-source Minfin.com.ua website and create a clean dataset for analytical visualization.
🛠 Technologies
Python 3.x

requests: For fetching HTML content.

BeautifulSoup: For parsing data within the HTML.

re (Regular Expressions): To extract only the clean numeric value from complex text (e.g., "aprx. 1020010 people").

Pandas: For data cleaning and exporting to Excel.

⚙️ Project Challenges
AJAX Support: The site's archive is not loaded by changing pages, but rather via AJAX requests (hidden data loading). The script simulates these AJAX queries to fetch all older months.

Data Cleaning: Ensuring that only clean, cumulative numerical values are extracted from the scraped information

✨ Result
As a result of the project, a clean and analytical form of military casualty data has been obtained in the file named russia_military_casualties.xlsx
