# Project Setup Guide (Pip & Venv)

This guide explains how to set up your environment using Python's native `venv` module and `pip`. We have a python version 3.13, please make sure you have the same version.

---

## Step 1: Create a Virtual Environment
This creates a local folder (usually named `.venv`) that contains your isolated Python executable.

```bash
# Create the virtual environment
# Windows:
python -m venv .venv

# macOS/Linux:
python3 -m venv .venv
```

## Step 2: Activate a Virtual Environment
```bash
.venv\Scripts\activate

# Windows (PowerShell):
.\.venv\Scripts\Activate.ps1

# macOS/Linux:
source .venv/bin/activate
```

## Step 3: Install Libraries
```bash
pip install --upgrade pip

# Install requirements
pip install -r requirements.txt

# Ensure Jupyter Lab is installed in this environment
pip install jupyterlab
```

## Step 4: Run Jupyter Lab
```bash
jupyter lab
```

## Important:
To run the code, you need to add the dataset in the root folder.
Also, we tried a few things during this assignment, the main file is 
assignment.ipynb, which is the file that was based to create our documentation and
presentation.


crack_segmentation.ipynb was another attempt with tensorflow.