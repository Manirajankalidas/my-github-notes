# 🚀 GitHub Learning Roadmap (Beginner → Advanced)

Learn Git & GitHub step by step — 30 days, simple daily goals.  
🕒 Recommended: 30–45 mins per day

---

## 🧩 WEEK 1 — Basics & Foundations

- [ ] **Day 1:** Understand Git vs GitHub  
  - What is version control?  
  - Difference between Git (local tool) & GitHub (cloud hosting).  
  - 🔗 [Git Basics](https://git-scm.com/about)

- [ ] **Day 2:** Install & Configure Git  
  ```bash
  sudo apt install git
  git config --global user.name "Your Name"
  git config --global user.email "youremail@example.com"
  git config --list
  ```

- [ ] **Day 3:** Create Local Repo & Commit Changes  
  ```bash
  mkdir my-first-repo && cd my-first-repo
  git init
  echo "Hello Git" > README.md
  git add README.md
  git commit -m "Initial commit"
  ```

- [ ] **Day 4:** Connect Local Repo to GitHub  
  - Create repo on GitHub  
  - Connect using remote:  
    ```bash
    git remote add origin https://github.com/username/repo.git
    git push -u origin main
    ```

- [ ] **Day 5:** Work with Files  
  - Add, edit, delete, and rename files  
  - Use `git add`, `git commit`, `git rm`, `git mv`, `git diff`

- [ ] **Day 6:** Use `.gitignore`  
  - Create `.gitignore` file  
  - Add unwanted files like:
    ```
    *.log
    __pycache__/
    .env
    ```

- [ ] **Day 7:** Mini Review Project  
  - Create a small text-based project  
  - Practice commits, push, pull  

---

## ⚙️ WEEK 2 — Branching, Merging & Collaboration

- [ ] **Day 8:** Learn Branching  
  ```bash
  git branch feature-1
  git checkout feature-1
  git merge feature-1
  ```

- [ ] **Day 9:** Handle Merge Conflicts  
  - Create & fix merge conflicts manually

- [ ] **Day 10:** Work with Remote Branches  
  ```bash
  git push origin feature-1
  git pull origin main
  git push origin --delete feature-1
  ```

- [ ] **Day 11:** Clone & Fork  
  - Clone: `git clone https://github.com/user/repo.git`  
  - Fork a public repo & make changes

- [ ] **Day 12:** Practice Pull Requests (PRs)  
  - Make PRs between branches  
  - Review and merge PRs in GitHub UI

- [ ] **Day 13:** Collaboration Tools  
  - Create issues, assign collaborators, use discussions

- [ ] **Day 14:** Weekly Review  
  - Practice branching, merging, and PRs

---

## 🧠 WEEK 3 — Intermediate GitHub Usage

- [ ] **Day 15:** Tags & Releases  
  ```bash
  git tag v1.0
  git push origin v1.0
  ```

- [ ] **Day 16:** Undoing Changes  
  ```bash
  git restore <file>
  git reset --hard HEAD~1
  git revert <commit-id>
  ```

- [ ] **Day 17:** Explore History  
  ```bash
  git log --oneline --graph --decorate
  git blame <file>
  ```

- [ ] **Day 18:** GitHub Pages  
  - Create simple HTML project  
  - Deploy via Settings → Pages

- [ ] **Day 19:** Markdown & README.md  
  - Add headings, code blocks, badges, tables  
  - Example:
    ```markdown
    # Project Title
    ![Badge](https://img.shields.io/badge/version-1.0-green)
    ```

- [ ] **Day 20:** Issues & Project Boards  
  - Create labels, milestones, and project board

- [ ] **Day 21:** Review Week 3  
  - Clean old branches, improve README

---

## 🚀 WEEK 4 — Advanced Git & Automation

- [ ] **Day 22:** Git Rebase  
  ```bash
  git checkout feature-branch
  git rebase main
  ```

- [ ] **Day 23:** Git Aliases & Stash  
  ```bash
  git config --global alias.lg "log --oneline --graph --decorate"
  git stash
  git stash apply
  ```

- [ ] **Day 24:** GitHub Actions Intro  
  - Learn CI/CD basics  
  - Example `.github/workflows/test.yml`
    ```yaml
    name: Python Test
    on: [push]
    jobs:
      build:
        runs-on: ubuntu-latest
        steps:
          - uses: actions/checkout@v4
          - name: Run Script
            run: echo "Hello GitHub Actions"
    ```

- [ ] **Day 25:** Secrets & Variables  
  - Add GitHub secrets (Settings → Secrets → Actions)

- [ ] **Day 26:** Code Review Practices  
  - Use inline comments & “suggest changes” in PRs

- [ ] **Day 27:** Manage Large Projects  
  - Learn `.gitattributes`  
  - Explore Git LFS for large files  
  - Understand submodules

- [ ] **Day 28:** SSH Keys & Tokens  
  - Generate SSH key  
    ```bash
    ssh-keygen -t ed25519 -C "your@email.com"
    ```
  - Add to GitHub SSH keys section

- [ ] **Day 29:** Automate Releases  
  - Use GitHub Actions to auto-create version tags/releases

- [ ] **Day 30:** Final Review & Portfolio Repo  
  - Create your own full project:  
    - Code + Commits  
    - Branching  
    - README.md  
    - GitHub Pages  
    - CI Workflow  
  - 🎯 Upload it to your profile!

---

## 🧭 Bonus Topics (Optional)

- [ ] Git Hooks (pre-commit actions)
- [ ] GitHub API
- [ ] Contributing to open-source projects
- [ ] Managing organizations & teams

---

✅ **Tip:** Use this file as your daily checklist in your GitHub repo.  
Commit your progress every day to stay consistent!
