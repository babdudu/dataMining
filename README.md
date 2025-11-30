# Data Mining Project

The repository root stays focused on project assets (`Project.ipynb`, `requirements.txt`, etc.).  
All virtual-environment files live inside `.venv/`, keeping Git history clean and navigation simple.

## Data Setup

Before running the project, you need to download the dataset files and place them in the `Input/` folder.

1. **Download the data files from Canvas:**
   - Navigate to: https://canvas.aubh.edu.bh/courses/2583/files/406467?wrap=1
   - Download all 4 required files:
     - `transactions_2019data.csv`
     - `cards_data.csv`
     - `users_data.csv`
     - `fraud_labels.json`

2. **Place the files in the Input folder:**
   - Create an `Input/` folder in the project root if it doesn't exist
   - Copy all 4 downloaded files into the `Input/` folder
   - The final structure should be:
     ```
     dataMining/
     ├── Input/
     │   ├── transactions_2019data.csv
     │   ├── cards_data.csv
     │   ├── users_data.csv
     │   └── fraud_labels.json
     ├── Project.ipynb
     ├── requirements.txt
     └── README.md
     ```

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

