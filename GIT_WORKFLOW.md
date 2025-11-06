# Basic Git Workflow for test-copilot-html

## 1. Clone the repository
Clone the repository to your local machine:
```bash
git clone https://github.com/johncm/test-copilot-html.git
cd test-copilot-html
```

## 2. Create and switch to a new branch (for new features or bug fixes)
```bash
git checkout -b feature/my-feature-name
```

## 3. Add or modify files
Edit code, add new files, or update existing files as needed.

## 4. Stage and commit changes
Stage your changes:
```bash
git add .
```
Commit your changes with a message:
```bash
git commit -m "Describe what you changed"
```

## 5. Push changes to GitHub
Push your branch to the remote repository:
```bash
git push origin feature/my-feature-name
```

## 6. Create a Pull Request (PR)
Go to https://github.com/johncm/test-copilot-html, and create a Pull Request from your branch to `main`.

## 7. Review and merge
Review your PR, respond to feedback, and when ready, merge it into `main`.

## 8. Update your local main branch
```bash
git checkout main
git pull origin main
```

## 9. Delete the feature branch (optional)
After merging, you can delete the feature branch locally and remotely:
```bash
git branch -d feature/my-feature-name
git push origin --delete feature/my-feature-name
```

---

_Repeat steps 2–9 for each new feature or bug fix!_