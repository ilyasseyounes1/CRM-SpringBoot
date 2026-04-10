# Collaboration Guide

## Team
- **Ilyasse** — 
- **Abdelhay** — 

## Workflow

### Before starting any task
```bash
git checkout main
git pull
git checkout -b feature/your-task-name
```

### When done
```bash
git add .
git commit -m "feat: short description"
git push origin feature/your-task-name
```
Then open a **Pull Request** on GitHub → ask the other to review → merge to `main`.

## Branch naming
```
feature/customer-crud
feature/auth-jwt
feature/react-login-page
fix/some-bug
```

## Rules
- Never push directly to `main`
- Always pull before starting a new branch
- One feature = one branch = one PR
