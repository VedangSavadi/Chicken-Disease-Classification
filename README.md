# Chicken-Disease-Classification

## Workflows

1. Update config.yaml
2. Update secrets.yaml [optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. update the dvc.yaml

# How to run?

## STEPS:
Clone the repository
https://github.com/VedangSavadi/Chicken-Disease-Classification

## STEP 01 - Create a conda evironment after opening the repository
    conda create -n cnncls python=8.8 -y conda activate cnncls

## STEP 02 - Install the requirements
    pip install -r requirements.txt

## Finally run the following command
    Python app.py

### Now, open up your local host and port

## DVC cmd
1. dvc init
2. dvc repro
3. dvc dag

# AWS-CICD-Deployment-With-Github-Actions
## 1. Login to AWS console.
## 2. Create IAM user for deployment.
    # with specific access
        1. EC2 access: It is virtual machine
        2. ECR: Elastic Container Registry to save your docker image in AWS
    # Description: About the deployment
        1. Build docker image of the source code
        2. Push your docker image to ECR
        3. Launch your EC2
        4. Pull your image from ECR in EC2
        5. Launch your docker image in EC2
    # Policy:
        1. AmazonEC2ContainerRegistryFullAccess
        2. AmazonEC2FullAccess
## 3. Create ECR Repo to store/save docker image
    - Save the URI: