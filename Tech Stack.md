
# ⚙️ Strik3Zone Tech Stack Overview

Strik3Zone is powered by a modular, high-performance tech stack designed to support:

💡 Custom player modeling

⚾ Fantasy league automation

📊 Real-time stat dashboards

🧠 Strategic content and tools

🏆 Tournament and prize pool management



---

🖥️ FRONTEND – Modern Web Interface

Tool	Purpose

Vue 3	Main reactive frontend framework
Vite	Lightning-fast dev/build tool with SSR support
Tailwind CSS	Utility-first styling system
TanStack Table	Interactive leaderboards with filters/sorting
Fuse.js	Fuzzy search and filtering in player tables
Chart.js	Dynamic visualizations for trends, stats, ranks
CKEditor5 Premium	Rich content editing for longform + CMS
VitePress	Markdown-powered docs and internal wiki system



---

🧠 BACKEND – API, Logic, and Models

Tool	Purpose

FastAPI	Backend REST API (ultra-fast async Python API)
Pydantic	Schema validation & type enforcement
SQLAlchemy or Tortoise ORM	DB interaction layer
PostgreSQL	Relational database for all structured data
Pandas + NumPy	Core modeling and statistical analysis
Streamlit	Admin dashboards and data input/monitoring
Celery (optional)	Background jobs and scheduled model updates



---

🧩 DATA, MODELS & STORAGE

Layer	Purpose

Statspiracy Repo	Central repository for models, metrics, formulas
CSV & JSON Exports	Model outputs pulled into WebApp
Google Drive	Shared access for visual/media assets, templates
GitHub	Version control (main repos: WebApp + Models)
Tally.so	Form and survey input (CRM, signups, league setup)
LeagueSafe	Prize pool management for leagues
Fantrax	Fantasy league hosting platform
Discord	Community, league comms, and live chat



---

🧠 AI, MODELS & PREDICTIONS

System	Description

STORM	Reliever reliability model (trust + leverage + performance)
ProspeX	Prospect progression and ranking model
Fantasy$Value	Auction dollar calculator based on positional value
UltiTeam	Franchise performance rating across fans, ownership, media
Tier Generator	Position/category-based tier assignments



---

🛠️ TOOLING & AUTOMATION

Tool/Script	Purpose

pull_model_data.py	Pulls CSV exports from metrics repo to WebApp
Streamlit Admin UI	Internal league management & player editing
FastAPI API Layer	Serves models to frontend
CSV / SQL View Loader	Imports model outputs to PostgreSQL



---

🎓 EDUCATION & CONTENT DELIVERY

Platform	Use Case

Substack	Weekly newsletters, previews, strategy
VitePress	Docs for models, guides, and tools
Markdown + PDF	eBooks, worksheets, longform guides



---

📦 INFRASTRUCTURE & DEPLOYMENT (Optional / Future)

Stack	Purpose

Netlify or Vercel	Frontend hosting & preview deploys
Render or Railway	FastAPI + PostgreSQL backend deployment
GitHub Actions	CI/CD for model refresh or deploy previews



---

🔁 Workflow Summary

Models Repo (Statspiracy)
   ↓ Python Models (STORM, ProspeX, etc.)
   → CSV Output / JSON
   ↓
WebApp (Vue + FastAPI)
   → PostgreSQL
   → Frontend Tables, Charts, Rankings
   → League Tools + CRM + User Input
   ↓
Fantrax + LeagueSafe + Discord
   → Real Leagues, Real Prizes, Real Community


---

✅ Ready to Scale

This stack is:

🔧 Modular – Easily add new sports, models, or league types

⚡ Fast – Powered by Vite + FastAPI

📊 Transparent – Built on real models, not opinions

🏆 Competitive – Real leagues, real payouts, real edge



---

Would you like this exported as:

📄 Markdown for your README.md?

📦 PDF one-pager for your docs or GitHub repo?

🌐 HTML snippet for your landing page?


Let’s lock it in and go live.

