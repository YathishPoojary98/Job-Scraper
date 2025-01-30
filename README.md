# 🖥️ Job Scraper for Python Developers

This Python script scrapes job listings from **TimesJobs** based on the **Python** keyword and filters out job postings that require a skill the user is unfamiliar with. The extracted job details are saved into individual text files.

---

## 🚀 Features

✅ **Live Job Scraping** – Fetches the latest Python job listings from TimesJobs.  
✅ **Skill-Based Filtering** – Excludes job postings that require skills the user is unfamiliar with.  
✅ **Automated Execution** – Runs continuously, scraping jobs every minute.  
✅ **Saves Data Locally** – Stores job details in separate `.txt` files inside a `Files` directory.  

---

## 🛠 Requirements

Ensure you have the following installed:

- **Python 3.x**
- **Libraries:** `requests`, `BeautifulSoup`, `lxml`

To install the required dependencies, run:

```bash
pip install requests beautifulsoup4 lxml
```

---

## 📥 Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YathishPoojary98/Job-Scraper.git
```

Navigate into the cloned directory:

```bash
cd Job-Scraper/Web scraping
```

### 2️⃣ Run the Script

Ensure Python is installed, then execute the following command:

```bash
python new.py
```

---

## 🎮 How It Works

1️⃣ **Enter the skill you are unfamiliar with** – The script will filter out job postings requiring this skill.  
2️⃣ **Scrapes the latest Python job listings** from **TimesJobs**.  
3️⃣ **Checks the job's posted date** – Only considers jobs posted within a **few days**.  
4️⃣ **Saves job details** (Company Name, Required Skills, More Info) into separate text files inside the `Files/` directory.  
5️⃣ **Repeats every 1 minute**, continuously fetching new jobs.  

---

## 📂 Example Output

After running the script, job postings will be saved as individual text files inside the `Files/` directory:

```
Files/
├── 0.txt
├── 1.txt
├── 2.txt
└── ...
```

Each text file contains:

```
Company Name: Example Company
Required Skills: Python, Django, Flask
More Info: https://www.timesjobs.com/example-link
```

---

## ⚠️ Disclaimer

This script scrapes job listings from **TimesJobs**, which may violate **their Terms of Service**. Use it for educational purposes only. Excessive scraping may lead to an IP ban.

---
