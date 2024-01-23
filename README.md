# spinda

Updated for Python >= 3.11.7

## Setup

```
# Create a virtual environment folder
python -m venv .venv

# Activate the virtual environment
# (below is Powershell on Windows; other platforms have their own activation scripts)
.\.venv\scripts\Activate.ps1

# If activated successfully, you should now see (.venv) prepended to your terminal

# Update venv's pip
python -m pip install --upgrade pip

# Install dependencies
pip install -r requirements.txt

# Run the script
python spinda.py
```

Then visit http://127.0.0.1:5015/ in your web browser to generate a Spinda sprite.

## TODO

- Return a simple HTML page with a button/link to refresh the page and generate a new Spinda
- Apply code formatting ([Black](https://black.readthedocs.io/en/stable/)?)
