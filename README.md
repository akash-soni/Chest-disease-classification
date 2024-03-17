# Chest-disease-classification
e-classification


# Chest-Disease-Classification-from-Chest-CT-Scan-Image


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n ./venv python=3.8 -y
```

```bash
conda activate venv
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```



## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)



### MLFLOW DAGSHub Connection URI

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/akash-soni/Chest-disease-classification.mlflow \
MLFLOW_TRACKING_USERNAME=akash-soni \
MLFLOW_TRACKING_PASSWORD=09da3f5fa31c7da7bb4d94298a2e83c3277877a3 \
python script.py
```

### Run from Bash Terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/akash-soni/Chest-disease-classification.mlflow

export MLFLOW_TRACKING_USERNAME=akash-soni

export MLFLOW_TRACKING_PASSWORD=09da3f5fa31c7da7bb4d94298a2e83c3277877a3
```