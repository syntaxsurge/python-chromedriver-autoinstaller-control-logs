# Control logs of chromedriver_autoinstaller

You can see the original project here:
[chromedriver-autoinstaller](https://pypi.org/project/chromedriver-autoinstaller/)

## Installation

You can install the modified package directly from GitHub using pip:

#### For Windows:
```bash
pip install git+https://github.com/syntaxsurge/python-chromedriver-autoinstaller-control-logs.git
```

#### For Linux:
```bash
pip3 install git+https://github.com/syntaxsurge/python-chromedriver-autoinstaller-control-logs.git
```

## Usage

If `log_level=logging.ERROR`, it logs only errors, not warnings nor infos.

You can use it like this:

```python
import chromedriver_autoinstaller
chromedriver_autoinstaller.install(log_level=logging.ERROR)
```
