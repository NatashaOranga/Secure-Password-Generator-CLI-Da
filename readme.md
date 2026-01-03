# Use the same .gitignore from Day 1, but ADD this line:
echo "expenses.json" >> .gitignore
```

This keeps your personal financial data private!

**Complete `.gitignore`:**
```
# Python
__pycache__/
*.py[cod]
*.pyc

# Virtual environments
venv/
env/

# IDE
.vscode/
.idea/
.DS_Store

# Personal data (IMPORTANT!)
expenses.json
expenses_backup_*.json
