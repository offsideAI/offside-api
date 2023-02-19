# offside-api

## Prerequisites

```
* Clean anaconda
conda install anaconda-clean

anaconda-clean

conda install pytorch torchvision torchaudio -c pytorch-nightly

conda install jupyter pandas numpy matplotlib scikit-learn tqdm

* Troubleshooting
conda install -n myvenv ipykernel --update-deps --force-reinstall

pip install ipykernel --upgrade

```

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


conda env list

conda deactivate
```

* Ensure that you have the latest version of pip in your virtual env
```
pip install --upgrade pip
```

* Pin dependencies using requirements.txt

```
pip install -r requirements.txt
```
```
fastapi[all]
diffusers==0.4.0
transformers
scipy
ftfy
```

* Pin dev dependencies using dev-requirements.txt

```
pip install -r dev-requirements.txt
```

```
mypy
ruff
black
ipykernel
```
