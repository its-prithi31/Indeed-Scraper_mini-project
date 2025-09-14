### **Indeed Job Scraper**



**The Indeed Job Scraper is a Python-based project that extracts job listings from Indeed**

**. It collects job details such as job title, company, location, salary, rating, date posted, job URL, and (optionally) job descriptions. This tool is useful for job seekers, recruiters, and researchers who want to analyze job market trends or track specific opportunities.**



### **Features**



* **Search and extract job listings based on keywords and location**
* **Gather details: title, company, location, salary, rating, posting date, job URL**
* **Optionally scrape full job descriptions**
* **Supports multiple pages for comprehensive data collection**
* **Saves results into CSV format**



### **Technologies Used**



* **Python (main language)**
* **Selenium → browser automation for dynamic content**
* **Requests + BeautifulSoup → fetch and parse job descriptions**
* **Pandas → store and manage data in CSV**
* **webdriver-manager → auto-manage ChromeDriver**

* 
**### Usage**



**Run the scraper:**



* **python scraper.py**



**By default, it searches for "Python Developer" jobs in "Chennai".**



### **Output**



**A CSV file like:**



* **indeed\_jobs\_20250914\_123456.csv**
