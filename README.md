# Lab 1 — Your First Pull Request
### Software Construction · Month 1, Week 1

---

## 🎯 Objective

Implement the `fibonacci(n)` function in Python, write passing unit tests,
follow PEP 8 coding standards, and submit your work via a Pull Request on GitHub.

---

## 📋 Tasks

| # | Task | File |
|---|------|------|
| 1 | Fork this repo and clone your fork | — |
| 2 | Create a branch named `feature/your-name` | — |
| 3 | Implement `fibonacci(n)` | `fibonacci.py` |
| 4 | Ensure all tests pass | `test_fibonacci.py` |
| 5 | Fix any Ruff violations | `fibonacci.py` |
| 6 | Open a Pull Request using the template | GitHub |

---

## ⚙️ Setup

```bash
# 1. Clone your fork
git clone https://github.com/YOUR-USERNAME/sw-construction-lab1.git
cd sw-construction-lab1

# 2. Create your branch
git checkout -b feature/your-name

# 3. Install dependencies
pip install ruff pytest

# 4. Run the tests (they will fail until you implement the function)
pytest test_fibonacci.py -v

# 5. Check code style
ruff check .
ruff format --check .
```

---

## ✅ Acceptance Criteria

Your PR will only be reviewed once **all CI checks pass**:

- `ruff check .` → 0 violations
- `ruff format --check .` → 0 formatting issues  
- `pytest test_fibonacci.py -v` → all tests green

---

## 📐 Coding Standards

- Follow **PEP 8** — enforced by Ruff (line length 79, 4-space indent)
- Use a **Google-style docstring** — the stub already has the structure
- Use **Conventional Commits**: `feat(lab1): add fibonacci function with tests`
- No commented-out code, no magic numbers, meaningful variable names

---

## 🌿 Branch & PR Workflow

```
main  ←── Pull Request ←── feature/your-name
```

1. **Never commit directly to `main`**
2. Open your PR against `main`
3. Fill in the PR template completely
4. Add your lab partner as a reviewer

---

## 📤 Submission

Open your Pull Request before **Wednesday 23:59**.  
Your PR description is part of your grade — fill it in carefully.

---

## 🆘 Getting Help

- Office hours: **Tuesday & Thursday 2–4 PM**
- Ask a demonstrator during the lab session
- Post in the course Slack channel `#lab-help`
