# md-toc

Walks a Markdown document and emits a nested table of contents.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install md-toc
```

## Usage

```python
from md_toc import mdToc

result = mdToc("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
