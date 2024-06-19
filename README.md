BreadcrumbsPLPBasicGitAssignment
# PLPBasicGitAssignment

This repository contains a simple demonstration of basic Git and GitHub workflows.

## Steps Followed

### Task 1: Repository Setup

1. **GitHub Repository Creation:**
   - Created a new repository on GitHub named `PLPBasicGitAssignment`.
   - Initialized it with a README file.

### Task 2: Local Setup

2. **Local Folder Setup:**
   - Created a new folder named `PLPBasicGitAssignment` on the local machine.
   - Opened a terminal or command prompt and navigated to the created folder.
   - Initialized a new Git repository in the local folder with `git init`.

3. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository with:
     ```bash
     git remote add origin https://github.com/PointParticle/PLPBasicGitAssignment.git
     ```

### Task 3: Making Changes

4. **Create a File:**
   - Created a new text file named `hello.txt` inside the local folder.
   - Added the message "Hello, Git!" to the file.

5. **Committing Changes:**
   - Staged the changes with:
     ```bash
     git add hello.txt
     ```
   - Committed the changes with:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

### Task 4: Pushing to GitHub

6. **Pushing to GitHub:**
   - Pushed the committed changes to the GitHub repository with:
     ```bash
     git push -u origin main
     ```

### Verification

7. **Verification:**
   - Confirmed that the `hello.txt` file and commit message are visible in the GitHub repository.
