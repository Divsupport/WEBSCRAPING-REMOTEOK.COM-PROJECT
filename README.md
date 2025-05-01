# WEBSCRAPING-REMOTEOK.COM-PROJECT
This project scrapes remote tech jobs from RemoteOK.Com using Python. It extracts job titles, company names, and skill tags, then saves the data into a CSV file. It uses `requests`, `BeautifulSoup`, and `pandas` to fetch, parse, and organize job listings for easy analysis.


# 🕸️ Web Scraping RemoteOK.com Project

This project scrapes remote developer job listings from [RemoteOK.com](https://remoteok.com) using Python.

## 🎯 Project Goal

To extract **job titles**, **company names**, and **job tags** from RemoteOK and save the data in a CSV file for analysis or job search reference.

## 🧰 Tools Used

- `requests` – to fetch the website content  
- `BeautifulSoup` – to parse and extract data from HTML  
- `pandas` – to organize data and export it to CSV  

## 🛠️ Steps Performed

1. **Send a request** to the RemoteOK job listings page  
2. **Parse the HTML** with BeautifulSoup  
3. **Find each job post** using specific HTML tags  
4. **Extract**:
   - Job title
   - Company name
   - Tags (e.g., Python, React, etc.)
5. **Store the data** in a list of dictionaries  
6. **Convert to a DataFrame** using pandas  
7. **Save results** as `remote_jobs.csv`  
8. Optionally mount Google Drive to save the file in Colab

## ✅ Output

A clean CSV file containing remote tech job listings:
- `Title`
- `Company`
- `Tags`

## 📁 Example Output

| Title               | Company     | Tags                   |
|---------------------|-------------|------------------------|
| Backend Developer   | RemoteTech  | Python, Django, AWS    |
| Frontend Engineer   | CodeSpace   | React, JavaScript      |

## 📌 Note

This project is built for educational purposes and respects RemoteOK’s public job listings.

---

### 🙋‍♂️ Author

**Divine Tochukwu Oguamanam** 

