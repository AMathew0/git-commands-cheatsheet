```markdown
# 🧯 Git Troubleshooting

## ❗ Merge Conflicts

```bash
# See conflicts
git status
# After resolving
git add .
git commit

🧹 Undo Commit

git reset --soft HEAD~1      # Keep changes
git reset --hard HEAD~1      # Discard everything

💣 Detached HEAD

git checkout -b recover-branch

🧙 Recover Deleted Branch

git reflog
git checkout -b <branch> <commit-hash>
