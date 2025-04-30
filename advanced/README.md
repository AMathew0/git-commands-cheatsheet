# 🚀 Advanced Git Commands

Useful for more complex workflows and debugging.

## 🔍 Cherry-pick

```bash
git cherry-pick <commit-hash>

⚙️ Rebase

git rebase main
git rebase -i HEAD~3

🪝 Git Hooks
Client-side (pre-commit, pre-push)
Server-side (pre-receive)

📘 Reflog

git reflog
git checkout <commit-hash>

🏷 Tagging
git tag v1.0
git push origin v1.0
