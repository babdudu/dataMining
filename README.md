# Data Mining Project

The repository root stays focused on project assets (`Project.ipynb`, `requirements.txt`, etc.).  
All virtual-environment files live inside `.venv/`, keeping Git history clean and navigation simple.

## Quick Start

1. **Open a terminal** in the project root (the folder containing this README).
2. **Create the virtual environment (first time only):**
   ```bash
   python -m venv .venv
   ```
3. **Activate the environment:**
   - PowerShell: `.\.venv\Scripts\Activate.ps1`
   - Command Prompt: `.venv\Scripts\activate.bat`
   - Git Bash: `source .venv/Scripts/activate`
4. **Install dependencies:** `pip install -r requirements.txt`
5. Launch `Project.ipynb` (or any scripts) while the environment is active.

## Recreating / Updating the Environment

If the environment ever becomes corrupted or you need to refresh it:

```bash
rm -rf .venv         # or use Explorer to delete the folder on Windows
python -m venv .venv
source .venv/Scripts/activate  # use the appropriate activate script for your shell
pip install -r requirements.txt
```

> `.venv/` is ignored by Git, so feel free to remove and recreate it whenever needed.

