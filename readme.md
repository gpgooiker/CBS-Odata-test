# Labor market data per sector

## Setup instructions (macOS and Windows)

### Requirements
- Python 3.13 installed
- Internet connection for package installation
- If you're using Visual Studio Code, you'll need the 'Jupyter' extension

### macOS

1. Open Terminal and go to the project folder:
```bash
cd "/path/to/CBS Odata-test"
```

2. Create a virtual environment with Python 3.13:
```bash
python3.13 -m venv cbs-env
```

3. Activate the environment:
```bash
source cbs-env/bin/activate
```

4. Upgrade pip and install dependencies:
```bash
pip install --upgrade pip
pip install cbsodata
```

5. Verify Python version:
```bash
python --version
```

### Windows (PowerShell)

1. Open PowerShell and go to the project folder:
```powershell
cd "C:\path\to\CBS Odata-test"
```

2. Create a virtual environment with Python 3.13:
```powershell
py -3.13 -m venv cbs-env
```

3. Activate the environment:
```powershell
.\cbs-env\Scripts\Activate.ps1
```

4. Upgrade pip and install dependencies:
```powershell
python -m pip install --upgrade pip
pip install cbsodata
```

5. Verify Python version:
```powershell
python --version
```

## Documentation of the CBS Odata library
https://pypi.org/project/cbsodata/