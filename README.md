A small API client to interact with newTrackon in Python.

Contains all [API functions](https://newtrackon.com/api)

Available on [PyPI](https://pypi.org/project/newtrackon/)

## Installation

```bash
pip install newtrackon
```

## Usage

```python
import newtrackon

client = newtrackon.Client()

trackers = client.working_trackers()
```
