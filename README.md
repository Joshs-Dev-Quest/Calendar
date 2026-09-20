# Calendar
# Documentation
The documentation is present with the tool `zensical`.
To build these locally, an additional Python tool must be installed.

## With uv
```bash
uv sync --group docs
```

## With pip
```bash
pip install zensical
```

The documentation can then be built locally and displayed in the browser.

```shell
zensical serve
```

The documentation can be downloaded under the link [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the
documentation.
Calendar Application for the modul DevOps.
The calendar shows all events I enter for me and others.

# Requirements
This project is build with:
- Python 3.12.3
- Flask 3.1.3
- gunicorn 26.
- prometheus-flask-exporter
- Pytest 9.1.1

# Installation and usage
## Installation
```bash
cd parent/dir/of/custom/folder/location
git pull https://github.com/Joshs-Dev-Quest/Calendar.git
cd Calendar
```
## Setup with [UV](https://docs.astral.sh/uv/getting-started/installation/)
```bash
uv sync
```

## Setup with pip
```bash
python3 -m venv .venv && source .venv/bin/activate

pip install -r requirements.txt
```

## Usage
TBD
```bash
```
