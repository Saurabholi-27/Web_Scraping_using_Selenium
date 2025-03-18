# 📰 News Scraping Using Selenium

This project is a web scraping application designed to extract trending news headlines from various popular news websites using Selenium. The goal is to automate the process of collecting and organizing news data efficiently.

---

## 🚀 Project Overview
This project automates the process of scraping trending news headlines from popular news platforms like BBC and Hindustan Times. The extracted data includes the following details:
✅ Headline Title  
✅ News Source  
✅ Publication Time  
✅ Link to the Article  

---

## 🛠️ Tech Stack

- **Python** – Programming language used for automation and data handling  
- **Selenium** – Web scraping and browser automation  
- **BeautifulSoup** – Parsing HTML and extracting data  
- **Pandas** – Data manipulation and cleaning  
- **VS Code** – Code editor used for development

---

## 📌 Key Features
✔️ Automated extraction of trending headlines  
✔️ Handling dynamic content using Selenium  
✔️ Clean and structured output in a DataFrame  
✔️ Error handling and retry mechanism for robust scraping  

---

## 📂 Project Structure
├── data/                    # Folder to store extracted data  
├── src/                     # Source code files  
│   ├── scraper.py           # Script to scrape news data  
│   ├── utils.py             # Helper functions for cleaning and saving data  
├── README.md                # Project documentation  
├── requirements.txt         # List of dependencies  
└── main.py                  # Main script to execute the scraper  

--- 

## 🏃‍♂️ How to Run
**1. Clone the repository**
```
git clone https://github.com/your-username/news-scraping.git  
cd news-scraping
```
**2. Create a virtual environment**  
```
python -m venv venv  
source venv/bin/activate  
```
**3. Install dependencies**  
```
pip install -r requirements.txt
```
**4. Open the project in VS Code**  
```
code .
```
**5. Run the scraper**  
```
python main.py
```

---

## 📊 Sample Output
| **Headline**  | **Source** | **Time** | **Link** |
| ------------- | ------------- | ------------- | ------------- | 
| "AI breakthrough in healthcare"  | BBC  | 2 hours ago	| Read more |
| "Stock market hits new high"  | Hindustan Times  | 1 hour ago | Read more |

---

## 🚧 Challenges Faced
- Handling JavaScript-based dynamic loading of content  
- Managing CAPTCHA and anti-scraping mechanisms  
- Ensuring consistency in data extraction from different sites

---

## 🎯 Future Scope
- Adding more news sources  
- Scheduling periodic scrapes using Cron Jobs  
- Creating a dashboard for real-time updates

---

## 👨‍💻 Author
**Saurabh** – Data Science Enthusiast 👨‍💻

---

**⭐ If you found this project helpful, give it a star! 🌟**
