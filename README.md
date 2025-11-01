

# SEO Link Health Checker

🔗 **Live App:** [https://brokenlinkchecker-production.up.railway.app/](https://brokenlinkchecker-production.up.railway.app/)  
💻 **GitHub Repo:** [https://github.com/Overwatch886/broken_link_checker/](https://github.com/Overwatch886/broken_link_checker/)

## Key Features

- **Web Scraping:** Scan any site for links—internal and external.
- **Broken Link Detection:** Instantly flag non-working, redirected, or unhealthy URLs.
- **SEO Health Reporting:** See results that matter for usability and search ranking.
- **Simple Web UI:** Built with Flask, Requests, and BeautifulSoup.
- **Cloud Hosted:** Runs on Railway for speed and availability.

## How It Works

- Enter any website URL.
- The app crawls and checks the status of each link (OK, broken, redirected).
- Results are shown in a table—easy to search and review.

## Project Structure

```text
SEO LINK HEALTH CHECKER
│
├── templates/        # Flask web templates
│   └── index.html    # Home page
├── app.py            # Main Flask application
├── requirements.txt  # Dependency list
├── Procfile          # Railway deployment configuration
└── README.md         # Project documentation
```

**Core Files:**
- `app.py`: Main Flask web app, handles logic and routes
- `templates/`: HTML templates for pages
- `requirements.txt`: Lists all dependencies
- `Procfile`: Required for Railway deployment
- `README.md`: Project documentation

## Tech Stack

- **Languages/Libraries:** Python, Flask, Requests, BeautifulSoup
- **Deployment:** Railway (cloud, free-tier compatible)

## How to Run Locally

```bash
git clone https://github.com/Overwatch886/broken_link_checker.git
cd broken_link_checker

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate      # For Windows
source venv/bin/activate   # For Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

# Open http://localhost:5000/ in your browser
```

## Future Improvements

- Add scheduled scans for periodic health checks
- Integrate email or webhook notifications
- Export results in CSV/Excel format
- Add CI/CD pipelines for automated testing and deployment
- Enhance SEO-specific analysis and recommendations

## Key Learnings

- Designed an end-to-end web scraping and analytics workflow for SEO
- Used Flask and Python’s ecosystem for rapid development and clean code
- Learned to deploy easily to Railway
- Practiced best practices in modularization and error handling

## Contact

- **Email:** [olawuyiisrael42@gmail.com](mailto:olawuyiisrael42@gmail.com)
- **GitHub Issues:** [Open an issue](https://github.com/Overwatch886/broken_link_checker/issues)

