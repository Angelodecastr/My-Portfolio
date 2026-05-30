# My Portfolio - MkDocs Portfolio

My personal portfolio website built with MkDocs.

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Angelodecastr/My-Portfolio.git
cd My-Portfolio


# Create virtual environment (only if venv folder does NOT exist)
python -m venv venv

# Activate virtual environment (do this EVERY time you work)
.\venv\Scripts\activate.bat

# Use this if: First time setup OR after creating a new venv  
pip install mkdocs mkdocs-material

#### on git

# 1. Make changes to your content
#    - Edit existing .md files in docs/ folder
#    - Or create new .md files

# 2. Preview locally to see your changes
mkdocs serve
# Check if everything looks correct at http://127.0.0.1:8000/My-Portfolio/

# 3. Save your changes to Git (optional but recommended)
git add docs/
git add mkdocs.yml (if you changed it)
git commit -m "Describe your changes here"

# 4. Push to GitHub main branch (optional)
git push

# 5. Then deploy to GitHub Pages
mkdocs gh-deploy --force --clean




### for git ignore if some changes
# Add new .gitignore
git add .gitignore

# Commit with message
git commit -m "Update .gitignore to ignore additional files"

# Push to GitHub
git push





Notes
accidentally commit to github
#git rm -r --cached site
#git rm -r --cached .vscode

venv/ folder = Auto-generated (don't commit to Git)

site/ folder = Auto-generated (don't commit to Git) it safe it was create on gitignore

Always activate venv first before running any mkdocs commands
