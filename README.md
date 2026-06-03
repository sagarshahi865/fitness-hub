# Fitness Hub

Django Fitness Platform by Team Codex

Quick start:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Features implemented:
- User Profile with edit
- Dashboard basic chart
- Goals CRUD
- Nutrition (Diet) CRUD
- Progress CRUD
- Exercise library (seeded)
- Store with cart (session), checkout simulation

Next steps: polish UI, add tests, and integrate payments.
 
CI: A GitHub Actions workflow was added at `.github/workflows/ci.yml` to run migrations and tests on push/PR to `main`.

Run tests locally:

```bash
python manage.py test
```
>>>>>>> 583b04a (feat: complete Fitness Hub implementation — models, views, templates, tests, CI)
