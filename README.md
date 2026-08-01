# Jenkins Day 02 - GitHub Integration

## 🎯 Objective

To integrate Jenkins with GitHub using a Freestyle Project and understand how Jenkins automatically fetches source code from a GitHub repository to perform build operations.

---

# 📖 Project Description

This project demonstrates the integration of Jenkins with GitHub using Source Code Management (SCM). Jenkins connects to a GitHub repository, clones the latest source code into its workspace, executes build commands, and displays the build results in the Console Output.

This is the first step toward implementing Continuous Integration (CI) in a DevOps environment.

---

# 🛠 Tools Used

- Windows 11
- Java 25
- Jenkins 2.575
- Git
- GitHub
- VS Code

---

# 📚 Topics Covered

- What is Git?
- What is GitHub?
- What is Source Code Management (SCM)?
- Jenkins and GitHub Integration
- Repository URL Configuration
- Freestyle Project
- Build Now
- Console Output
- Workspace

---

# 📂 Project Structure

```
jenkins-day02-github-integration/

│── README.md
│── notes.txt
│── index.html
│── screenshots/
```

---

# ⚙ Build Commands

```bat
dir

echo Jenkins Successfully Downloaded Files

echo Build Successful
```

---

# 📄 Expected Console Output

```
Started by user

Cloning Repository

Fetching origin

Checking out Revision

index.html

README.md

notes.txt

Jenkins Successfully Downloaded Files

Build Successful

Finished: SUCCESS
```

---

# 🎓 What I Learned

- Git is a Version Control System.
- GitHub is used to store Git repositories online.
- Jenkins can connect to GitHub repositories.
- SCM (Source Code Management) allows Jenkins to fetch source code.
- Jenkins clones the latest code into its workspace.
- Jenkins automatically executes build commands.
- Continuous Integration (CI) automates the build process.

---

# 💼 Real-Time Use Case

In software companies, developers push code to GitHub. Jenkins automatically detects the latest changes, downloads the updated code, builds the project, runs tests, and prepares it for deployment. This automation reduces manual work and improves software quality.

---

# 📸 Screenshots

- GitHub Repository
- Jenkins SCM Configuration
- Repository URL
- Build Now
- Console Output
- Build Success

---

# 🎯 Outcome

Successfully integrated Jenkins with GitHub and automated the build process using a Freestyle Project.

---

# 👩‍💻 Author

**Subalakshmi K**

Cloud & DevOps Learner