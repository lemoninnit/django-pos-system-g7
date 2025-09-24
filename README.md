# Django POS System
A Point of Sale system built with Django featuring role-based access for admin, manager, 
and teller users.
## Features
- User authentication with different roles
- Admin user management
- Manager product management and sales reports
- Teller POS system with transaction processing
- Responsive web interface
## Installation
1. Clone the repository
2. Create virtual environment: `python -m venv env`
3. Activate environment: `source env/bin/activate` (Linux/Mac) or `env\Scripts\activate` 
(Windows)
4. Install requirements: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Create superuser: `python manage.py createsuperuser`
7. Run server: `python manage.py runserver`
## Technology Stack
- Django
- SQLite (can be configured for other databases)
- HTML/CSS/JavaScript
# Add, commit, and push README
git add README.md
git commit -m "setup(project): readme_file"
git push origin setup/project/readme_file:setup/project/readme_file
Go to GitHub, create a Pull Request for this branch, have it reviewed, then merge it.
Step 4: Set Up .gitignore and Environment
# Switch back to main and pull changes
git checkout main
git pull origin main
# Create new branch for gitignore
git checkout -b setup/project/gitignore_file
Create .gitignore file with this content:
gitignore
# Django
*.log
*.pot
*.pyc
__pycache__/
db.sqlite3
media/
# Environment
env/
venv/
ENV/
env.bak/
venv.bak/
# IDE
.vscode/
.idea/
*.swp
*.swo
# OS
.DS_Store
Thumbs.db
# Coverage reports
htmlcov/
.coverage
.coverage.*
coverage.xml
*.cover
.hypothesis/
.pytest_cache/
# Jupyter Notebook
.ipynb_checkpoints
# Package files
*.egg
*.egg-info
dist/
build/
eggs/
parts/
var/
sdist/
develop-eggs/
.installed.cfg
lib/
lib64/
# Installer logs
pip-log.txt
pip-delete-this-directory.txt
# Unit test / coverage reports
htmlcov/
.tox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*.cover
.hypothesis/
.pytest_cache/
# Translations
*.mo
# Static files
/staticfiles/
# macOS
.DS_Store
