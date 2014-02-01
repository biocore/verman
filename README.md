verman
======

Python module version information

This module provides a light object for describing package version information. It is expected that this object will be imported by the top level ``__init__.py``. For instance:

```python
from verman import Version
verman_version = Version('verman', 1, 1, init_file=__file__)
__version__ = str(verman_version)
```
