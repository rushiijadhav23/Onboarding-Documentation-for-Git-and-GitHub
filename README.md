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
   https://github.com/ChaiCode/example-repo.git
   ```
2. Clone the repository:
   ```bash
   git clone https://github.com/ChaiCode/example-repo.git
   ```
3. Navigate into the cloned folder:
   ```bash
   cd example-repo
   ```

**Attach a screenshot of the terminal showing the clone process.**

---

## Basic Git Commands

### Commonly Used Commands
1. Check repository status:
   ```bash
   git status
   ```
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
5. Pull updates from GitHub:
   ```bash
   git pull
   ```
6. View commit history:
   ```bash
   git log
   ```

**Attach screenshots for each command being executed in the terminal.**

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

**Attach screenshots of branch creation and merging.**

---

## Pull Requests (PR)

### Creating a Pull Request
1. Push your branch to GitHub.
2. Go to the repository on GitHub and click **Pull Requests**.
3. Click **New Pull Request**.
4. Add a description and request reviewers.

**Attach screenshots of the pull request process.**

---

## Best Practices
- **Commit Regularly**: Avoid large, infrequent commits.
- **Descriptive Messages**: Write meaningful commit messages.
- **Pull Updates**: Regularly pull changes to minimize conflicts.

---

## Deliverables Checklist
1. A properly formatted `README.md` file with embedded screenshots.
2. At least **5 meaningful commits**.
3. A **sample branch** created and merged with the main branch.
4. At least one **pull request** demonstrating the workflow.
