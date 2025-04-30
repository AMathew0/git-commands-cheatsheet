```markdown
# 🧩 Git Workflows

## 🔄 Feature Branch Workflow

```bash
git checkout -b feature/my-feature
# Work, then:
git push origin feature/my-feature

🚀 Git Flow (optional)

main: production
develop: staging
feature/, release/, hotfix/

🌐 Fork & Upstream

git remote add upstream <original-url>
git fetch upstream
git rebase upstream/main
