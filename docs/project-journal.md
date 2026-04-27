## 2026-04-25 – Project setup and GitHub basics

### 🎯 What I did
- Created a new GitHub repository
- Added initial project structure:
  - README.md
  - LICENSE
  - .gitignore
  - docs/project-journal.md
- Updated README with project description
- Learned how GitHub repository interface works (commits, files, activity)

### 🧠 What I learned
- Difference between README and project journal
- What .gitignore does and why it is important
- What REST APIs are at a basic level
- How GitHub commits represent project history
- How GitHub Projects (Kanban) can be used for task management

### 💡 Key insights
- GitHub is not just file storage, but a full project management tool
- Documentation is as important as code in real projects
- Small commits and structured work reflect professional workflow

### 📌 Next steps
- Set up GitHub Project (Kanban board)
- Define first tasks (API integration setup)
- Choose first API to implement (weather/news/crypto)

---

## 2026-04-25 – Kanban board setup and task planning

### 🎯 What I did
- Created a GitHub Project Kanban board for task management
- Added initial project tasks to the “To Do” column:
  - Project setup tasks
  - API integration tasks
  - Data processing tasks
  - Dashboard UI tasks
  - Documentation tasks

### 🧠 What I learned
- How Kanban boards are used in real software development
- How to break a project into small, manageable tasks
- Importance of structured planning in software projects
- Difference between planning and implementation phases

### 💡 Key insights
- Large software projects are always divided into small tasks
- Each task should represent one clear, actionable step
- Planning work properly makes development more structured and efficient

### 📌 Next steps
- Prioritize tasks in the Kanban board
- Start first implementation task (project setup and environment configuration)
- Begin implementing backend logic step by step

---

## 2026-04-27 – Project setup completion, Git workflow and development environment

### 🎯 What I did
- Finalized the initial project structure with separated folders:
  - `api/` for backend logic and API integration  
  - `ui/` for future dashboard / user interface  
  - `docs/` for documentation and project journal  

- Created and configured essential project files:
  - `.gitignore` (to exclude sensitive and unnecessary files like `venv` and `.env`)
  - `requirements.txt` (to manage Python dependencies)
  - `journal.md` (to track daily progress)

- Set up and tested Python development environment:
  - Created and activated virtual environment (venv)
  - Installed required libraries (e.g. requests, python-dotenv)
  - Understood how dependencies are isolated per project

- Worked with Git and GitHub workflow:
  - Practiced staging, committing, and pushing changes
  - Resolved authentication issue caused by incorrect GitHub account login
  - Successfully pushed project changes to repository

- Tested Git ignore behavior and confirmed that sensitive files (like `.env`) are properly excluded from version control

---

### 🧠 What I learned
- How a real software project structure is organized and why separation of concerns matters
- How Git workflow works in practice (status → add → commit → push)
- How authentication issues in Git are commonly caused and resolved
- How virtual environments isolate project dependencies
- Why `.gitignore` is critical for security and clean repositories
- How API keys should be handled securely using `.env` files instead of hardcoding

---

### 💡 Key insights
- Project setup is not “just preparation” — it is the foundation for scalable development
- Git errors are usually not complex bugs, but configuration or authentication issues
- Keeping secrets out of GitHub is a fundamental security practice
- A clean folder structure improves long-term maintainability and clarity
- Real development work is structured, incremental, and task-driven (Kanban + small steps)

---

### 📌 Next steps
- Start API FOUNDATION phase
  - Choose first external API (weather, news, or crypto)
  - Implement first `GET` request using `requests`
  - Parse and display JSON response
- Begin building core backend logic inside `api/` folder
- Start transforming project from setup phase into real data-driven application