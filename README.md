## PYTHON 3.11 required

## to create virtual env

```
python -m venv .venv
```

## to run virtual env

```
source .venv/scripts/activate
```

## to install dependencies

```
pip install -r requirements.txt
```

## to update requirements

```
pip freeze > requirements.txt
```

### run this in terminal shell (python) to fix polish lang error

```
 import nltk
 nltk.download('punkt_tab')
```
