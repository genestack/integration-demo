# Install the Genestack ODM SDK

## Instructions

To run the exercises in this session, please install the Genestack ODM SDK and ensure you have a stable Python 3.10 environment.

## Step 1 — Check Your Python Version

The SDK requires Python 3.10.x.
```bash
python3 --version
```

If the version shown is not Python 3.10, install it using the instructions below.

### Windows

Download Python 3.10: https://www.python.org/downloads/release/python-3100/  
✔ Make sure to tick "Add Python to PATH"

### macOS (Homebrew)
```bash
brew install python@3.10
```

### Linux
```bash
sudo apt-get update
sudo apt-get install python3.10 python3.10-venv python3.10-dev
```

## Step 2 — (Optional) Create a Virtual Environment
```bash
python3.10 -m venv genestack-env
```

Activate the environment:

### Windows
```bash
genestack-env\Scripts\activate
```

### macOS / Linux
```bash
source genestack-env/bin/activate
```

You should now see:
```bash
(genestack-env)
```

## Step 3 — Install the SDK
```bash
python3 -m pip install odm-sdk
```

## Step 4 — Verify the Installation
```bash
python3 -m pip show --verbose odm-sdk
```

Expected output:
```
Name: odm-sdk
Version: 1.61.0
Summary: SDK for interacting with the Open Data Manager
```

If errors appear, the installation may not have completed correctly.

## Additional Resources

For more detailed instructions and troubleshooting, please review the user guide at:  
https://q001-demo.trial.genestack.com/user-docs/tools/odm-sdk/installation/
