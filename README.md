# Office365 To Do CLI Tool
A command-line interface tool using Selenium to scrape the Office365 To Do app.

## Setup
1. Create virtual environment
```
python3 -m venv .venv --prompt to-do
```
2. Activate .venv
```
source ./.venv/bin/activate
```
3. Install dependencies
```
python3 -m pip install -r requirements.txt
```
4. Set Environmental Variables for Login
```
export EMAIL=[EMAIL]
export PASS=[PASS]
```

## Using the Tool
Get My Day
```
todo
```
