# RECIPE: Creating a New Working Python Project Environment

# 1. Create a GitHub repository
#    - Navigate to GitHub
#    - Create a new repo

# 2. Create a Codespace
#    - Open the repository on GitHub
#    - Click Code → Codespaces → Create codespace on main

# 3. Open the Codespace in local VS Code
#    - Open VS Code on your local machine
#    - Use the GitHub Codespaces extension
#    - Open the active Codespace in VS Code

# 4. Inspect the project structure
#    - Create a requirements.txt file

# 5. Open a Bash terminal
#    - Terminal → New Terminal
#    - Make sure the shell is Bash

# 6. Create a virtual environment
#    - Run: python3 -m venv venv

# 7. Activate the virtual environment
#    - Run: source venv/bin/activate
#    - Confirm activation by seeing (venv) in the terminal prompt

# 8. Exclude the virtual environment from version control
#    - Create a .gitignore file
#    - Add venv/ to the .gitignore file

# 9. Install required packages
#    - In requirements.txt:
#       add necessary packages (plotly==6.5.1)
#    - Run:
#       pip install -r requirements.txt
#       pip install ipykernel

# 10. Update requirements.txt
#     - Run: pip freeze > requirements.txt
#     - This records exact package versions for reproducibility

# 11. Set up Python files for development
#     - Create a .py file
#     - Install Jupyter extension
#     - Add cell markers (# %%) for interactive execution

# 12. Verify Python interpreter
#     - Ensure VS Code is using the virtual environment interpreter
#     - Select venv/bin/python if needed

# 13. Commit and push changes
#     - git add .
#     - git commit -m "Initial project setup"
#     - git push
