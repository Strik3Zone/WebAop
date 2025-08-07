# 🧱 Strik3Zone Web App – Full Tech Stack Overview

## ⚙️ Frontend

- **Vue 3** – Reactive frontend framework
- **Vite** – Frontend build tool (with SSR)
- **Tailwind CSS** – Utility-first styling framework
- **TanStack Libraries**:
  - `@tanstack/table` – Advanced tables, filtering, sorting
  - `@tanstack/query` – Data-fetching and caching
  - `@tanstack/virtual` – Virtualized rendering for performance
  - `@tanstack/form`, `@tanstack/pacer`, `@tanstack/ranger` – UI/UX helpers
- **Fuse.js** – Fuzzy search for player/stats matching
- **Chart.js** – Graphs & data visualizations
- **CKEditor5 Premium** – Rich text + markdown editing
- **VitePress** – Documentation and static content builder

---

## 🧠 Backend

- **Python** – Backend language
- **FastAPI** – High-speed web framework and RESTful API
- **Pydantic** – Schema and data validation
- **PostgreSQL** – Primary relational database
- **SQLAlchemy** or **Tortoise ORM** – DB modeling and interaction
- **Streamlit** – Internal dashboard & data science UI
- **Pandas**, **NumPy**, **SciPy** – Data wrangling and modeling
- **Celery** – Async task queue (scheduled data pulls, background tasks)

---

## 📚 Data & Storage

- **PostgreSQL Tables**:
  - Player Stats, Team Info, Fantasy Leagues
  - Projections, Prospect Tracker, CRM, Insider Hub, etc.
- **CSV Import/Export** – Stat downloads, raw data input/output
- **Web Scraping** – `Selenium`, `BeautifulSoup`, `Playwright` for automation
- **External APIs** – FanGraphs, Baseball Reference, sportsbooks, fantasy sites
- **Cloud Storage** – CDN (e.g., AWS S3, Cloudinary) for media assets

---

## 📊 Content & Docs

- **VitePress** – Site docs, project wiki, glossary
- **Markdown + HTML + CKEditor5** – eBooks, content blog, longform
- **PDF Generator** – Downloadable guides and printable tools
- **Substack Integration** – Weekly newsletter + blog sync

---

## 👥 Community / CRM / Auth

- **Discord Bot** – Live bullpen alerts, server sync, posting
- **Reddit Crosspost API** – Post publications to Reddit
- **Tally.so** – Embedded forms and lead capture
- **User Auth & Membership System**:
  - Login, VIP tier, role-based access
  - CRM tables for user roles, lead status, participation
- **Analytics & Event Tracking** – Engagement metrics, link tracking

---

## 🧪 Models & Tools

- **Strik3Zone Fantasy Tools**
  - `STORM` – Reliever Reliability Model
  - `$Value` Auction Calculator – Fantasy dollar projections
  - `ProspeX` Tracker – Prospect scoring and progression
  - `Team Master DB` – Team metadata, history, value index
  - `Performance + Fan Value Index` – Market analytics
  - `Course Betting System` – Learn-to-bet module
  - `Futures Tracker` – MLB/NFL/PGA seasonal odds movement
  - `Games Hub` – Survivor, Pick’em, Brackets, Confidence Pools

- **Formula Engine (Spreadsheet/Backend Hybrid)** – 
  Calculates scores, tiers, $ value in Google Sheets or API-connected modules

- **Custom API Layer** – Syncs all modules: frontend ↔ backend ↔ database

---

## ✅ Output Formats Available

- `✅ Markdown` – For GitHub, documentation
- `📄 PDF` – Printable version
- `📊 CSV` – For spreadsheet import
- `🌐 HTML` – For site embed or blog

---
