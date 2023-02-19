# offside-api

## Steps

* Create virtual env as follows

```
python3 -m venv myvenv
```

* Activate virtual env as follows

```
source myvenv/bin/activate
```

* Ensure that you have the latest version of pip in your virtual env
```
python -m pip install --upgrade pip
```

* Pin dependencies using requirements.txt
```
fastapi[all]
diffusers==0.4.0
transformers
scipy
ftfy
```

* Pin dev dependencies using dev-requirements.txt

```
mypy
ruff
black
ipykernel
```
