## 📱 Smartphone Market Analysis using Web Scraping – Flipkart Case Study  

### 🔍 Project Overview  
This project focuses on extracting **real-time smartphone data from Flipkart** using Python-based web scraping (BeautifulSoup + Requests).  

The smartphone market is fast-changing — with new launches, fluctuating prices, and evolving customer preferences. By collecting and analyzing this data, the project demonstrates **end-to-end data analysis workflow**:  

- Data Collection (Web Scraping)  
- Data Cleaning & Transformation  
- Data Analysis & Visualization (Power BI)  

The insights generated cover:  
- 📊 Price distribution across smartphone models  
- 💸 Discount patterns across brands  
- ⭐ Consumer rating behavior  
- ⚡ Key specification comparisons (RAM, Battery, Display, Processor, Camera)  

---

### 📂 Data Source  
- **Website:** [Flipkart Smartphones](https://www.flipkart.com/)  
- **Target Data:**  
  - Brand & Model  
  - Price & Original Price  
  - Discount %  
  - Ratings  
  - Key Specs (RAM, ROM, Display, Battery, Camera, Processor)  

---

### 🛠️ Tools & Libraries  
- **Python** – Programming  
- **Requests** – Sending HTTP requests  
- **BeautifulSoup** – HTML parsing  
- **Pandas** – Data storage & cleaning  
- **Power BI** – Visualization  

---

### 🚀 Methodology  

#### 1. Setting up Environment  
- Imported libraries & defined base URL for Flipkart smartphones.  

#### 2. Website Structure Analysis  
- Used browser dev tools to identify HTML tags & classes for:  
  - Product Name  
  - Price  
  - Ratings  
  - Specifications  

#### 3. Scraping Process  
- Sent HTTP requests with headers (User-Agent).  
- Parsed HTML with BeautifulSoup.  
- Extracted details into Python lists.  

#### 4. Pagination Handling  
- Implemented looping for multiple pages of results.  

#### 5. Data Storage  
- Structured into **Pandas DataFrame**.  
- Exported as `flipkart_smartphones.csv` for further cleaning.  

---

### ⚠️ Challenges & Considerations  

- **Pagination Limitations** → Only 984 records extracted vs. 9,284 shown.  
- **Dynamic Content (JavaScript/AJAX)** → Some listings may load after scroll.  
- **Anti-Scraping Measures** → Rate limits & bot detection can block requests.  
- **Selector Accuracy** → Missing items if tags/classes change.  
- **Ethical Use** → Always respect Flipkart’s Terms of Service.  

---

### ✅ Closing Note  
The scraping phase successfully created a **raw dataset of Flipkart smartphones**. The next step will be **Data Cleaning & Transformation**, preparing it for insightful Power BI dashboards to reveal key market patterns.  



