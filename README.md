# smart-store-benp

Starter files to initialize the smart sales project.

-----

## Project Setup Guide (1-Mac/Linux)

Run all commands from a terminal in the root project folder. 

### Step 1A - Create a Local Project Virtual Environment

```shell
python3 -m venv .venv
```

### Step 1B - Activate the Virtual Environment

```shell
source .venv/bin/activate
```

### Step 1C - Install Packages

```shell
python3 -m pip install --upgrade -r requirements.txt
```

### Step 1D - Optional: Verify .venv Setup

```shell
python3 -m datafun_venv_checker.venv_checker
```

### Step 1E - Run the initial project script

```shell
python3 scripts/data_prep.py
```

-----

## Project Setup Guide (2-Windows)

Run all commands from a PowerShell terminal in the root project folder.

### Step 2A - Create a Local Project Virtual Environment

```shell
py -m venv .venv
```

### Step 2B - Activate the Virtual Environment

```shell
.venv\Scripts\activate
```

### Step 2C - Install Packages

```shell
py -m pip install --upgrade -r requirements.txt
```

## Module 2
- Create folder named utils in the root folder.
- Create file named logger.py
- Copy file from professor's directory into own logger.py file
- Create folder named scripts in the root folder.
- Create file named data_prep.py
- Copy file from professor's directory into own data_prep.py file (make sure all file names are lowercase and check spelling)
- Execute python script data_prep.py (I had to install pandas and restart terminal to run this)

```shell
py scripts/data_prep.py
```

- Add-Commit-Push to GitHub

```shell
git add .
git commit -m "Update Readme File"
git push
```

- Module 3 Addition
- Added/ran test data scrubber, 13 tests ran OK
- Looked at previous function in py script to add str.upper().str.strip()
- Edited the raw data files as there was a trackback error that occured becasue the raw data had null values
- After this looks like it ran okay

- Update Readme File

- Module 4 Addition
- Copied script from the Topic P4 assignment page
- Ran into issues with path - changed DW_Path 
- Could not append table after first commit (had to delete smart_sales.db and create new) - only first table populated
- Had a column error, renamed it on the prepared file
- Ran successful the last time after deleting the initial db file 

## What's Next?
- Coming soon!

-----

## Initial Package List

- pip
- loguru
- ipykernel
- jupyterlab
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- pyspark==4.0.0.dev1
- pyspark[sql]
- git+https://github.com/denisecase/datafun-venv-checker.git#egg=datafun_venv_checker