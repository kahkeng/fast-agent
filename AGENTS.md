# Initialize
```
source /venv/bin/activate
```

# Format
```
uv run scripts/format.py
```

# Lint
```
uv run scripts/lint.py
```

# Tests
```
python -m pytest tests/unit -v
python -m pytest tests/integration -v
```
