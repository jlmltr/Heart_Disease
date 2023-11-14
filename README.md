# Heart_Disease
Predicting heart diseases by using advanced automated EDA, feature engineering, preprocessing and evaluating the optimal model from a set of 20 models. Displaying results with a visualisation



```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt

```

activate

```
source .venv/bin/activate
```

Freezing pip installs:

```
# put all install libs as list in requirements.txt 
pip freeze > requirements.txt
```

Cleaning cache:

```
find . -name "*.pyc" -exec rm -f {} \;
find . -type d -name __pycache__ -exec rm -r {} +

```