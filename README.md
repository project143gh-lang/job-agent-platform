# Job Agent Platform

An intelligent job agent platform with web interface. Automate your job search with AI-powered assistance and manage applications efficiently.

## 📸 Screenshot



**Access the platform:** Run `python main.py` and open `http://localhost:5000` in your web browser.

## Features

### 🤖 AI-Powered Features
- **Job matching**: AI algorithms match your skills with job postings
- **Application tracking**: Monitor all your job applications in one place
- **Resume optimization**: Get suggestions for improving your resume
- **Cover letter generator**: AI-assisted cover letter creation

### 📊 Dashboard
- **Application overview**: Status dashboard for all applications
- **Timeline view**: Visual timeline of application progress
- **Statistics**: Success rates, response times, etc.
- **Quick actions**: One-click apply, follow-up, reject

### 🌐 Web Interface
- **Responsive design**: Works on desktop, tablet, and mobile
- **Navigation menu**: Header with quick links
- **Sidebar**: Agent settings and preferences
- **Real-time updates**: Live status updates without page refresh

### 📧 Communication
- **Email integration**: Automated status update emails
- **Template library**: Pre-written follow-up emails
- **Message tracking**: When employers open your emails
- **Automated reminders**: Follow-up date alerts

### 🔧 Management
- **Agent personas**: Switch between different agent personalities (Scout, Researcher, Closer, Accountant)
- **Task automation**: Schedule recurring tasks
- **Preference settings**: Customize agent behavior
- **Export data**: Download reports and analytics

## 🚀 Quick Start

```bash
# 1. Install dependencies
pip install flask

# 2. Run the application
python main.py

# 3. Open in browser
# Visit: http://localhost:5000
# Or explore the web interface:
# - http://localhost:5000/zoom
# - http://localhost:5000/house
# - http://localhost:5000/360
```

## 🛠️ Project Structure

```
hermes/
├── main.py             # Flask application entry point
├── SPEC-job-agent.md   # Detailed job agent specification
├── tasks/              # Task management
│   ├── todo.md         # Daily tasks and priorities
│   └── plan.md         # Strategic planning document
├── job-agent/          # Job agent modules
│   └── web/            # Web interface templates
│       ├── index.html  # Main dashboard
│       ├── zoom.html   # Zoom view mode
│       ├── house.html  # House view mode
│       └── 360.html    # 360° view mode
├── ponytail-main (2).zip  # Additional resources
├── services/           # Microservices
│   ├── scoring_service.py
│   ├── scheduler_service.py
│   ├── research_service.py
│   ├── portfolio_service.py
│   ├── notion_service.py
│   ├── monitor_service.py
│   ├── email_service.py
│   ├── deployment_service.py
│   └── browser_service.py
├── kernels/            # Core brain and persona management
│   ├── kernel.py       # Main kernel
│   ├── brain.py        # Core reasoning engine
│   └── persona_manager.py # Persona switching
└── personas/           # Agent persona definitions
    ├── scout.yaml
    ├── researcher.yaml
    ├── closer.yaml
    └── accountant.yaml
```

## 📋 Personas

### Scout
- Finds job opportunities
- Researches companies
- Generates leads
- Reports market trends

### Researcher
- Analyzes job markets
- Gathers intelligence
- Deep research reports
- Competitive analysis

### Closer
- Handles client communication
- Negotiates offers
- Manages relationships
- Deals finalization

### Accountant
- Financial tracking
- Billing and invoicing
- Revenue analysis
- Budget management

## 📁 Services Architecture

### Scoring Service
- Job match scoring
- Applicant ranking
- Compatibility algorithms

### Scheduler Service
- Task scheduling
- Recurring jobs
- Cron-like functionality

### Research Service
- Market research
- Company data gathering
- Trend analysis

### Portfolio Service
- Application tracking
- Status management
- History logging

### Notion Service
- Database integration
- Sync with Notion
- Data persistence

### Monitor Service
- System health monitoring
- Performance metrics
- Alert notifications

### Email Service
- Automated emails
- Template management
- Send/Track status

### Deployment Service
- Platform deployment
- Configuration management

### Browser Service
- Automated browsing
- Job board scraping
- Data extraction

## 📜 License

MIT

---

**K.bhalavardt, MIT Student**
