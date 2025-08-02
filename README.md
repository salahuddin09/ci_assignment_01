# ci_assignment_01

This repository contains two GitHub Actions workflows:

1. **List Changed Files**  
   - Runs on every push to `main`.  
   - Lists files changed since the last commit.  
   - Uploads the list as an artifact.  

2. **Dependent Workflow**  
   - Runs only if the first workflow completes successfully.  
   - Downloads and displays the list of changed files.  
