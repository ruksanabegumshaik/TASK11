# CI/CD Pipeline using GitHub Actions

Created a Python application using `app.py`, `test_app.py`, and `requirements.txt`.

Installed the required packages:
# pip install pytest flake8

This command installs `pytest` for running automated tests and `flake8` for checking code quality and coding standards.

Executed the application:
# py application_source/app.py

This command runs the Python application and verifies that the code is working correctly.

Performed code quality checks:
# flake8 .

This command scans the project files and detects coding style issues, syntax errors, and formatting problems.

Executed unit tests:
# py -m pytest

This command runs the test cases written in `test_app.py` and verifies whether the application behaves as expected.

Created GitHub Actions workflow files:
# build.yml
# test.yml
# deploy.yml

These files automate the Build, Test, and Deploy stages of the CI/CD pipeline.

Initialized the Git repository:
# git init---This command initializes an empty Git repository to start version control.

# git branch -M main---This command creates and sets the main branch.

# git add .---This command adds all project files to the staging area before committing.

# git commit -m "Initial Commit"---This command saves the current version of the project in the local repository.

Connected the local repository to GitHub:
# git remote add origin <repository-url>---This command links the local repository with the remote GitHub repository.


# git push -u origin main---This command uploads all project files to GitHub and sets the upstream branch.

Configured the CI/CD pipeline using GitHub Actions.

The Build workflow installs dependencies and verifies the build process.

The Test workflow runs automated tests using Pytest and validates application functionality.

The Deploy workflow simulates application deployment after successful build and test stages.

Verified successful execution of Build, Test, and Deploy workflows from the GitHub Actions tab.

Commands Used:

pip install pytest flake8
py application_source/app.py
flake8 .
py -m pytest
git init
git branch -M main
git add .
git commit -m "Initial Commit"
git remote add origin <repository-url>
git push -u origin main
