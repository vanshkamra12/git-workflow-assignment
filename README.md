# Git & GitHub Workflow Assignment

**Author:** Vansh Kamra ([vanshkamra27@gmail.com](mailto:vanshkamra27@gmail.com))  
**Repository URL:** [https://github.com/vanshkamra12/git-workflow-assignment](https://github.com/vanshkamra12/git-workflow-assignment)

---

## 📌 Project Overview
This repository satisfies the requirements for the **Git & GitHub Workflow Assignment**, demonstrating a comprehensive version control lifecycle starting entirely from a local environment, through branching, merging, `.gitignore` configuration, undo operations (`git reset`), and remote integration with GitHub.

---

## 🗂 Project Structure
```text
.
├── .gitignore          # Configured to ignore *.log and temp/
├── about.html          # About page modified on the feature branch and merged into main
├── git_commands.txt    # Complete reference list of Git commands with 1-2 line explanations
├── index.html          # Home page created in initial commit and updated in commit 2
└── README.md           # Project documentation and assignment overview
```

---

## 🌳 Branching & Commit Topology
The branch history demonstrates:
1. `Initial commit`: Creation of `index.html` and `about.html`.
2. `Second commit`: Navigation and overview enhancements on `index.html`.
3. `Branch creation`: `feature` branch branched off from `main`.
4. `Feature commit`: Mission statement and team section added to `about.html`.
5. `Merge commit`: Merged `feature` back into `main` using `--no-ff` (preserving the branch graph).
6. `.gitignore commit`: Configured pattern exclusions for `*.log` and `temp/`.
7. `Undo Demonstration`: Tested commit undo via `git reset HEAD~1`.
8. `Documentation`: Added `git_commands.txt` and `README.md`.

---

## 💻 Summary of Commands Used
Refer to [git_commands.txt](git_commands.txt) for detailed line-by-line descriptions of all Git commands executed.
