# Data Mining Project Environment

This repository already includes a pre-created virtual environment folder named `dataMining`. The steps below show how to activate it (or recreate it if needed) and install the project dependencies listed in `requirements.txt`.

## Quick Start

1. **Open a terminal** in the project root (the same folder that contains `requirements.txt`).
2. **Activate the existing virtual environment (Windows PowerShell or Command Prompt):**
   - PowerShell: `.\dataMining\Scripts\Activate.ps1`
   - Command Prompt: `dataMining\Scripts\activate.bat`
   - Git Bash: `source dataMining/Scripts/activate`
3. **Install the dependencies:** `pip install -r requirements.txt`
4. You're ready to run the project inside the activated environment.

## Recreate the Environment (optional)

If you prefer to create a fresh virtual environment:

```bash
python -m venv dataMining
source dataMining/Scripts/activate  # Use the shell-appropriate activate script
pip install -r requirements.txt
```

These commands will regenerate the `dataMining` folder and set up all required packages.

