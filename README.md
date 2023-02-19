# offside-api

## Steps

* Create virtual env using venv

```
python3 -m venv myvenv


source myvenv/bin/activate
```

* Create virtual env using miniconda (recommended for Mac M1)

```
brew install miniforge
conda create --name myvenv python=3.8


conda activate myvenv


conda deactivate
```

* Ensure that you have the latest version of pip in your virtual env
```
pip install --upgrade pip
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
