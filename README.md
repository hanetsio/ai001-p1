# ai001-p1
NS Learnathon AI001 - Project 1

This repository contains student submissions for the ML Learnathon project. Each student creates a Jupyter notebook implementing a complete machine learning pipeline.

## 🚀 Quick Start

1. **Fork this repository**
2. **Clone your fork locally**
3. **Follow setup instructions below**
4. **Create your notebook in `notebooks/` folder**
5. **Submit via pull request**

## 📋 Requirements

- Python 3.10 or higher
- [uv](https://github.com/astral-sh/uv) package manager
- [Cursor](https://cursor.sh) IDE (recommended)
- Git

## 🛠️ Setup Instructions

### Install Required Tools

**uv Package Manager:**

*macOS/Linux:*
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

*Windows (PowerShell):*
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Cursor IDE:**
- Download from [cursor.sh](https://cursor.sh)
- Install and sign in

### Project Setup

1. **Fork and clone:**
```bash
git clone https://github.com/YOUR_USERNAME/ai001-p1.git
cd ai001-p1
```

2. **Setup environment:**
```bash
uv venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\activate   # Windows
```

3. **Install dependencies:**
```bash
uv sync
```

4. **Open in Cursor:**
```bash
cursor .
```

## 📝 Creating Your Project

### 1. Create Feature Branch
```bash
git checkout -b feature/your-name-project
```

### 2. Create Notebook
- In `notebooks/` folder
- Name: `surname_firstname_project.ipynb`
- Use Cursor's Jupyter integration

### 3. Add Dependencies
```bash
# Add packages as needed
uv add scikit-learn pandas matplotlib seaborn plotly
# uv automatically updates pyproject.toml
```

## 🔄 Submission

### 1. Commit Changes
```bash
git add notebooks/your_notebook.ipynb pyproject.toml uv.lock
git commit -m "Add [Your Name] ML project: [Brief Description]"
```

### 2. Push and Create PR
```bash
git push origin feature/your-name-project
```

Then create pull request on GitHub with:
- **Title:** `[Your Name] - [Project Title]`
- **Description:** Brief project summary

### 3. Post-Submission
- Export notebook to PDF/Markdown
- Upload to your personal website  
- Add link to NS profile: `ns.com/profile`

## 🛠️ Common Commands

```bash
# Add package
uv add package-name

# Remove package  
uv remove package-name

# Update all packages
uv sync

# Run notebook in Cursor
cursor notebooks/your_notebook.ipynb
```

## 🆘 Troubleshooting

**uv not found:**
```bash
# Restart terminal or source shell config
source ~/.bashrc  # Linux
source ~/.zshrc   # macOS
```

**Permission errors (Windows):**
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```
