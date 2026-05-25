# GitHub push commands

Run these commands in PowerShell, Git Bash, or Ubuntu terminal after extracting this folder.

Replace the repository name if you want a different one.

```bash
cd ethical-ai-operating-framework

git init
git add .
git commit -m "Initial ethical AI operating framework"

gh repo create ethical-ai-operating-framework --private --source=. --remote=origin --push
```

If Git asks for identity:

```bash
git config --global user.name "Kouta Suda"
git config --global user.email "gemaildatcam@gmail.com"
```

If the repo already exists:

```bash
git remote add origin https://github.com/moisuturewood/ethical-ai-operating-framework.git
git branch -M main
git push -u origin main
```

Suggested GitHub description:

```text
A practical framework for translating AI ethics into operational decision rules, risk taxonomies, and assistant behavior evaluation.
```

Suggested topics:

```text
ai-safety, ai-ethics, model-behavior, risk-taxonomy, ai-governance, human-ai-interaction
```
