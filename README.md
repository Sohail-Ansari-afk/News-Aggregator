# 🗞️ News Aggregator CLI App 🧠

Stay updated with the latest headlines right from your terminal!  
Fetch top news, filter by category, or search by keyword using this simple CLI app powered by NewsAPI.org.

---

## 🌟 Features

- 🔝 View top headlines from the US
- 📂 Filter news by categories like business, technology, and more
- 🔍 Search news by any keyword
- 🌐 Uses [NewsAPI](https://newsapi.org/) for real-time updates

---

## 🛠️ Requirements

- 🐍 Python 3.x  
- 📦 `requests` library

Install dependencies:

```bash
pip install requests
````

---

## 🔑 API Key Setup

1. Get your free API key from [https://newsapi.org](https://newsapi.org).
2. Replace the placeholder key in the script:

```python
API_KEY = "your_actual_api_key_here"
```

---

## 🚀 How to Run

1. 📥 Download or clone this repository.
2. 🧾 Open a terminal and navigate to the directory.
3. ▶️ Run the script:

```bash
python news_aggregator.py
```

---

## 🧭 Menu Options

Once the app starts, you’ll see:

```
1. View Top News
2. Filter by Category
3. Search by Keyword
4. Exit
```

### ➕ Examples:

* Choose **1** to see the latest US headlines
* Choose **2** to filter (e.g. `technology`, `sports`, etc.)
* Choose **3** to search (e.g. type `AI` or `climate`)
* Choose **4** to exit the app

---

## 📂 Supported Categories

* `business`
* `entertainment`
* `general`
* `health`
* `science`
* `sports`
* `technology`

---

## 💡 Sample Output

```text
1. Google announces new AI features
   Source: TechCrunch
   URL: https://techcrunch.com/article123
   Published: 2025-06-26
```

---

## 🛑 Note

🔐 Be careful with rate limits on your NewsAPI key.
Free accounts typically allow 100 requests per day.

---

## 📬 Feedback

Want to contribute or suggest a feature? Open an issue or pull request!

---

Made with ☕ and 📰 by \ Sohail-Ansari

