🚀 Git & GitHub Commands Cheat Shet

----

🔧 Basic Git Setup
---
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list

---
📂 Create / Initialize Repo
git init
git clone <repo-url>

---
📁 Check File Status
git status

---
➕ Add Files to Staging
git add <file>
git add .        # add all files

---
📝 Commit Changes
git commit -m "Commit message"
git commit -am "Add + commit tracked files"

---
🔄 Push & Pull
git push origin <branch>
git pull origin <branch>

---
🌿 Branches
git branch                # list branches
git branch <name>         # create branch
git checkout <name>       # switch branch
git checkout -b <name>    # create + switch
git branch -d <name>      # delete branch

---
🛠️ Stash Commands
git stash                  # save changes
git stash list             # view stashes
git stash pop              # apply & delete
git stash apply            # apply only

---
🔁 Merge & Rebase
git merge <branch>
git rebase <branch>

---
🗑️ Undo / Reset
git restore <file>                 # restore file
git reset --soft <commit>          # keep changes staged
git reset --hard <commit>          # delete all local changes

---
🆚 View History / Differences
git log
git log --oneline --graph
git diff
git diff --staged

---
🌐 Remote Commands
git remote -v
git remote add origin <url>
git remote remove origin
git remote rename origin backup

---
🧪 Tags
git tag
git tag <tag-name>
git push origin <tag-name>

---
📦 GitHub Authentication
gh auth login

---
🏗️ GitHub CLI (gh) Common Commands
gh repo create
gh repo clone <user>/<repo>
gh issue list
gh pr create
gh pr merge

---
🔍 Useful Shortcuts
git log --oneline
git status -s
git add -p

---
🔥 Most Used Daily Workflow
git pull
git checkout -b feature-branch
git add .
git commit -m "msg"
git push -u origin feature-branch
gh pr create
