The TaskFlow API dummy project gives you a realistic multi-file Python project to work with. It contains real code, real tests, intentional bugs, and a Dockerfile.
A real Flask REST API with multiple files, tests, a Dockerfile, and intentional bugs — purpose-built so you can practice every CodeCommit workflow from first push to pull requests.

codecommit-practice/ ├── app/ │ ├── app.py ← Flask REST API (GET/POST/PUT/DELETE /tasks) │ ├── config.py ← Env-based configuration │ ├── utils.py ← Validators, paginator, timestamp helpers │ └── notifications.py ← 3 intentional bugs for Ex 3 ├── tests/ │ └── test_app.py ← 20+ pytest tests ├── Dockerfile ├── requirements.txt ├── CHANGELOG.md └── .gitignore
