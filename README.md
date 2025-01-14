# Welcome to Git and GitHub at ChaiCode Cohort!

## Introduction
Welcome to ChaiCode Cohort! As part of our team, you'll work on exciting projects requiring seamless collaboration and efficient code management. This guide introduces you to Git and GitHub—essential tools for developers—and provides step-by-step instructions to get started within our organization.

## Basics of Git and GitHub
### What is Git?
Git is a distributed version control system that tracks changes in your code and enables collaboration with other developers. It allows you to:
- Keep a history of your project changes.
- Revert to previous versions if needed.
- Collaborate with team members efficiently.

### What is GitHub?
GitHub is a web-based platform for hosting Git repositories. It enhances team collaboration by providing:
- A centralized repository for your code.
- Tools for issue tracking, code reviews, and pull requests.
- Continuous integration and deployment options.

---

## Installation and Setup

### Installing Git
#### Windows:
1. Download Git from [git-scm.com](https://git-scm.com/).<img width="1022" alt="Screenshot 2025-01-14 at 11 48 53" src="https://github.com/user-attachments/assets/94c5913b-5707-4dcd-9286-90426010026c" />

2. Run the installer and follow the on-screen instructions.
3. Verify the installation:
   ```bash
   git --version
   ```
#### macOS:
1. Open Terminal and type:
   ```bash
   brew install git
   ```
2. Verify the installation:
   ```bash
   git --version
   ```

#### Linux:
1. Use your package manager:
   ```bash
   sudo apt-get install git    # For Debian/Ubuntu
   sudo yum install git        # For Fedora/Red Hat
   ```
2. Verify the installation:
   ```bash
   git --version
   ```

### Configuring Git
Set your user name and email:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
<img width="801" alt="Screenshot 2025-01-14 at 11 52 32" src="https://github.com/user-attachments/assets/079faa17-2b89-440c-bec6-76aace4610ee" />

### Creating a GitHub Account
1. Go to [github.com](https://github.com/) and click **Sign Up**.
2. Follow the instructions to create an account.
3. Verify your email address to activate your account.

---

## Cloning the ChaiCode Repository

1. Copy the repository URL:
   ```bash
   https://github.com/rushiijadhav23/Onboarding-Documentation-for-Git-and-GitHub.git
   ```
   <img width="2016" alt="Screenshot 2025-01-14 at 11 54 27" src="https://github.com/user-attachments/assets/57cbdce8-4627-4f6d-9acf-dddf462be057" />

2. Clone the repository:
   ```bash
   git clone https://github.com/rushiijadhav23/Onboarding-Documentation-for-Git-and-GitHub.git
   ```
   
3. Navigate into the cloned folder:
   ```bash
   cd Onboarding-Documentation-for-Git-and-GitHub
   ```
   <img width="1065" alt="Screenshot 2025-01-14 at 11 57 02" src="https://github.com/user-attachments/assets/327906f5-7cf1-4fe7-ba37-7e794d43b6c0" />

---

## Basic Git Commands

### Commonly Used Commands
1. Check repository status:
   ```bash
   git status
   ```
   <img width="1202" alt="Screenshot 2025-01-14 at 12 05 40" src="https://github.com/user-attachments/assets/0c51f99b-902f-4003-9a89-e03978735e11" />
   
2. Stage changes:
   ```bash
   git add <file>
   ```
3. Commit changes:
   ```bash
   git commit -m "Your message"
   ```
4. Push changes to GitHub:
   ```bash
   git push
   ```
   <img width="1233" alt="Screenshot 2025-01-14 at 12 08 00" src="https://github.com/user-attachments/assets/1df1f747-b0cd-4a07-8d18-b5e042a8a072" />
   <img width="2016" alt="Screenshot 2025-01-14 at 12 08 13" src="https://github.com/user-attachments/assets/5f4b4295-231a-4824-81be-a8a2df9f13f5" />

5. Pull updates from GitHub:
   ```bash
   git pull
   ```
6. View commit history:
   ```bash
   git log
   ```
   <img width="1221" alt="Screenshot 2025-01-14 at 12 11 07" src="https://github.com/user-attachments/assets/1535e935-c31a-4422-96f2-59d9c5293288" />

---

## Commit Message Rules
- Use the present tense (e.g., "Add feature" not "Added feature").
- Capitalize the first letter.
- Keep the message short (50 characters or less).
- Use prefixes for categorization:
  - `feat:` for new features.
  - `fix:` for bug fixes.
  - `docs:` for documentation updates.

**Examples:**
```bash
feat: Add tea selection feature
fix: Resolve login issue for tea enthusiasts
docs: Update README with chai varieties
```
<img width="2016" alt="Screenshot 2025-01-14 at 12 35 48" src="https://github.com/user-attachments/assets/da3c7ba7-a38c-47dd-be0e-bf61d56fda67" />

---

## Branching Workflow

### Branching Strategy
- **Main Branch**: Stable production-ready code.
- **Development Branch**: Active development.
- **Feature Branches**: Specific features or fixes.

### Creating and Switching Branches
1. Create a new branch:
   ```bash
   git branch feature/tea-menu
   ```
2. Switch to the branch:
   ```bash
   git checkout feature/tea-menu
   ```
3. Merge changes back to the main branch:
   ```bash
   git checkout main
git merge feature/tea-menu
   ```
4. Push the branch to GitHub:
   ```bash
   git push origin feature/tea-menu
   ```
   <img width="1345" alt="Screenshot 2025-01-14 at 12 19 46" src="https://github.com/user-attachments/assets/6771308c-1ae4-4e64-9a71-837e0e87c20a" />
   <img width="1345" alt="Screenshot 2025-01-14 at 12 23 21" src="https://github.com/user-attachments/assets/6e0dc9a0-a56a-4e1e-b6e9-1e5dcaa55fb1" />

---

## Pull Requests (PR)

### Creating a Pull Request
1. Push your branch to GitHub.
<img width="1345" alt="Screenshot 2025-01-14 at 12 23 21" src="https://github.com/user-attachments/assets/4b49869d-4f1d-4154-8fde-8f1f9129b50b" />

2. Go to the repository on GitHub and click **Pull Requests**. 
<img width="2016" alt="Screenshot 2025-01-14 at 12 21 15" src="https://github.com/user-attachments/assets/5d093d2a-2886-4628-9631-6082761ab828" />

3. Click **New Pull Request**.
<img width="2016" alt="Screenshot 2025-01-14 at 12 21 29" src="https://github.com/user-attachments/assets/7528d1bc-19b8-4c1d-a87b-bc13b4300f99" />


4. Add a description and request reviewers.
<img width="2016" alt="Screenshot 2025-01-14 at 12 21 42" src="https://github.com/user-attachments/assets/350af0b1-0c9d-4b3d-8674-a6c420b9750b" />
<img width="2016" alt="Screenshot 2025-01-14 at 12 21 54" src="https://github.com/user-attachments/assets/3bec95bc-815c-4159-bf55-9bf9130e805e" />
<img width="2016" alt="Screenshot 2025-01-14 at 12 23 12" src="https://github.com/user-attachments/assets/dff5237a-8a74-40ce-8133-da141c7d8243" />

---

## Best Practices
- **Commit Regularly**: Avoid large, infrequent commits.
- **Descriptive Messages**: Write meaningful commit messages.
- **Pull Updates**: Regularly pull changes to minimize conflicts.

---
