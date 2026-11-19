# marqueefrappes1n-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m marqueefrappes1n_kit.cli --help
```

```python
from marqueefrappes1n_kit.core import Marqueefrappes1nTool

tool = Marqueefrappes1nTool()
print(tool)
```

## Layout

```
marqueefrappes1n_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 marqueefrappes1n
