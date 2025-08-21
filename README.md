# 🕷️ Async Web Crawler & Keyword Finder

A blazing-fast **web crawler** written in **Python** 🚀  
This project is built with a special focus on **Asynchronous Programming** using `asyncio` and `aiohttp`.  
It crawls links, checks their availability, and searches for a keyword inside webpages — **all concurrently** for maximum performance ⚡.  

---

## 🔥 Programming Style
This project uses **Asynchronous Programming (async/await)** in Python:  
- Built with `asyncio` for managing event loops and concurrency  
- Uses `aiohttp` for **non-blocking HTTP requests**  
- Combines async tasks with synchronous code (`requests` + `BeautifulSoup`) for efficient parsing  
- Faster, scalable, and more resource-friendly compared to traditional synchronous crawlers  

✅ **Core Skill Demonstrated**: *Async/await concurrency with Python* 

---

## ✨ Features
- ⚡ **Asynchronous Crawling** (powered by `asyncio` & `aiohttp`)
- 🔗 **Link Extraction** from webpages
- ✅ **Availability Check** for each link (status < 400)
- 🔍 **Keyword Search** inside webpages (using BeautifulSoup)
- 🗑 **Duplicate Removal** to keep results clean
- 🖥 **Interactive CLI**: input website & keyword directly

---

## 📦 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/web-crawler.git
cd web-crawler
pip install -r requirements.txt
```

🚀 Usage

Run the script:
```bash
python crawler.py
```

Enter:

🌐 Website URL

🔑 Keyword you want to find

Output:

Total links found

Cleaned & valid links

Links containing your keyword

🛠 Requirements

Python 3.8+

Libraries:
- requests
- beautifulsoup4
- aiohttp

You can install them with:
```bash
pip install requests beautifulsoup4 aiohttp
```

📜 License

MIT License © 2025 MohammadReza Bidar
