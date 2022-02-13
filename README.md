# virtualenv
Creating a virtual environment for Machine Learning project

## Create a folder and create virtual environment inside that

```bash
py -m venv .venv
```
## Change directory to Scripts

```bash
cd .venv/Scripts/
```

## Activate the bat file
```bash
activate.bat
```

## Successful activation if you see like below

```bash
(.venv)......\.venv\Scripts>
```
## Install [pip](https://pip.pypa.io/en/stable/) packages
```bash
pip install jupyter
pip install pandas
```

## Create a requirements document by going back to root directory and typing below command
```bash
pip freeze -l > requirements.txt
```

## (Optional) If copy the environment of another project copy the data of requirements and type
```bash
pip install -r requirements.txt
```