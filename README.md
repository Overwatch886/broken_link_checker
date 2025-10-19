# 🔗 Broken Link Checker / SEO Link Health Checker

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://brokenlinkchecker-production.up.railway.app/)
[![GitHub](https://img.shields.io/badge/github-repo-blue)](https://github.com/Overwatch886/broken_link_checker/)

> **A powerful, easy-to-use web app that scans websites for broken, redirected, or unhealthy links — helping you maintain SEO health and a better user experience.**

🌐 **[Launch Live App](https://brokenlinkchecker-production.up.railway.app/)** | 💻 **[View Source Code](https://github.com/Overwatch886/broken_link_checker/)**

---

## ✨ Key Features

- **⚡ Fast Website Link Scanning** — Enter any URL to scan for broken, redirected, or unhealthy links
- **📊 Comprehensive Reports** — See detailed results with each link status (OK, broken, redirected)
- **🚀 SEO Health Checks** — Spot issues affecting search rankings and user experience
- **🎨 Simple, Modern Web UI** — Built with Flask, clean and easy to use
- **🛠️ Tech Stack** — Python · Flask · Requests · BeautifulSoup
- **☁️ Deploy Anywhere** — Ready-to-run on Railway or any modern cloud platform

---

## 🎯 How It Works

1. **Paste** any web page or site URL into the app
2. The system **scrapes** all linked URLs on that page
3. For each link, it **checks** HTTP status and classifies as working, broken, or redirected
4. **View** a searchable report table of all findings
5. **Download** or copy results for further analysis

---

## 📂 Project Structure

```
SEO LINK HEALTH CHECKER
│
├── templates/        # Flask web templates
│   └── index.html    # Home page
├── app.py            # Main Flask application
├── requirements.txt  # Dependency list
├── Procfile          # Railway deployment configuration
└── README.md         # Project documentation

```

### Core Files

- **`app.py`** — Launches the Flask web app and handles routes
- **`checker.py`** — Core class/function for web scraping and link validation
- **`templates/`** — Jinja2 HTML templates for landing and results pages
- **`requirements.txt`** — Lists dependencies (Flask, Requests, BeautifulSoup4, etc.)
- **`Dockerfile`** — Allows containerized builds for deployment

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Languages/Libraries** | Python, Flask, Requests, BeautifulSoup |
| **Deployment** | Railway (cloud, free-tier compatible), Docker-supported |

---

## 🚀 How to Run Locally

### Prerequisites
- Python 3.8+
- pip (Python package manager)
- Virtual environment (recommended)

### Installation Steps

```bash
# Clone the repository
git clone https://github.com/Overwatch886/broken_link_checker.git
cd broken-link-checker

# Create and activate a virtual environment
python -m venv venv

# For Windows
venv\Scripts\activate

# For Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

# Visit http://localhost:5000 in your browser
```

### Docker Deployment

```bash
# Build the Docker image
docker build -t broken-link-checker .

# Run the container
docker run -p 8080:5000 broken-link-checker
```

---

## ☁️ Deployment

This application is deployed via **Railway** using a Docker image, with flexible setup and scaling.

**🌐 [View Live App](https://brokenlinkchecker-production.up.railway.app/)**

---

## 🔮 Future Improvements

- [ ] Add scheduled scans for periodic health checks
- [ ] Integrate email or webhook notifications for new broken links
- [ ] Export results in CSV/Excel format
- [ ] Add CI/CD pipelines for automated testing and deployment
- [ ] Enhance SEO-specific analysis and recommendations
- [ ] Implement rate limiting and caching for better performance

---

## 📚 Key Learnings

- ✅ Built an end-to-end web scraping and health evaluation workflow
- ✅ Used Flask and Python's ecosystem for rapid development and clean code
- ✅ Learned how to containerize apps for easy cloud hosting (Railway, Render, etc.)
- ✅ Practiced best practices in modularization and error handling
- ✅ Saw how robust link checking can boost SEO, reliability, and site quality

---

## 📝 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Overwatch886/broken_link_checker/issues).

---

## 👤 Author

**Overwatch886**

- GitHub: [@Overwatch886](https://github.com/Overwatch886)

---

⭐ **If you find this project helpful, please give it a star!** ⭐
