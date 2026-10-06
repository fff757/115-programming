# AGENTS.md

- 所有的回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`（例如 `conda run -n iem_python python ...`、`conda run -n iem_python pip install ...`）。
- Empty course repo (`程設115`). Only `README.md` + Python `.gitignore` exist; no source, manifests, tests, or toolchain config yet.
- Do not invent build/test/lint commands; if adding a toolchain, document exact commands here.
- Respect `.gitignore`: `__pycache__/`, `*.pyc`, `.venv/`, `venv/`, `.pytest_cache/`, `coverage.xml`, etc.
