# DL-Project
# Workflows
Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml
How to run?
# STEPS:
Clone the repository

https://github.com/entbappy/Chicken-Disease-Classification--Project
STEP 01- Create a conda environment after opening the repository
conda create -n cnncls python=3.8 -y
conda activate cnncls
STEP 02- install the requirements
pip install -r requirements.txt
# Finally run the following command
python app.py
Now,

open up you local host and port
DVC cmd
dvc init
dvc repro
dvc dag
AWS-CICD-Deployment-with-Github-Actions