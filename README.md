# Deep_Learning_ML-Ops
Self project to create an end-to-end kidney disease image classifier using (VGG-16) and exploring the usage of MLflow, DVC and dockerization in the project.

# Steps done by me

1. Created the template or skeleton to implement project end to end
2. created environment installed required libraries & defined important functions in the utils.common file.
3. 


# Deep-Learning-Project-MLflow-DVC-MLOps


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/chiragshahu/Deep_Learning_ML-Ops
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n MLOps python=3.11 -y
```

```bash
conda activate MLOps
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/chiragshahu/Deep_Learning_ML-Ops.mlflow \
MLFLOW_TRACKING_USERNAME=chiragshahu \
MLFLOW_TRACKING_PASSWORD=9a7767ada97484e74a5a1b2cdc77ff8cae11a8e3 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/chiragshahu/Deep_Learning_ML-Ops.mlflow

export MLFLOW_TRACKING_USERNAME=chiragshahu 

export MLFLOW_TRACKING_PASSWORD=9a7767ada97484e74a5a1b2cdc77ff8cae11a8e3

```

