# vehicle_insurance_fraud_detection

Welcome to the Vehicle Insurance Fraud Detection project! 🚗🕵️‍♂️

## Workflows

1. **Configure Project:**
   - Update `config.yaml` to tailor settings.
   - Update `schema.yaml` for data schema changes.
   - Update the entity for better data understanding.
2. **Codebase Setup:**
   - Update the configuration manager in `src/config`.
   - Update various components for customization.
3. **Pipeline Enhancements:**

   - Update the data processing pipeline for efficiency.
   - Update the ML model pipeline for better predictions.

4. **Application Integration:**
   - Update `main.py` to incorporate the latest changes.
   - Update `app.py` for seamless app functionality.

## How to Run?

### Steps:

Clone the repository:

```bash
git clone https://github.com/RagalahariAkula-42/vehicle_insurance_fraud_detection
```

Create Conda Environment:

```bash
conda create -n vifd python=3.8 -y
conda activate vifd
```

Install Requirements:

```bash
pip install -r requirements.txt
```

Run the Application:

```bash
python app.py
```

Open Local Host:
Open your local host and port to interact with the application.

## MLflow Integration

For detailed experiment tracking, use MLflow.
Start MLflow UI with mlflow ui command.

## DAGshub Collaboration

Utilize DAGshub for enhanced version control.
Export environment variables for seamless collaboration:

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/****/******.mlflow
export MLFLOW_TRACKING_USERNAME=****
export MLFLOW_TRACKING_PASSWORD=********
```

## About MLflow

MLflow ensures production-grade model tracking.
Log and tag your models for effective monitoring.

## AWS-CICD-Deployment-with-Github-Actions

### 1. Login to AWS console.

### 2. Create IAM user for deployment

```bash
#with specific access

1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws


#Description: About the deployment

1. Build docker image of the source code

2. Push your docker image to ECR

3. Launch Your EC2

4. Pull Your image from ECR in EC2

5. Lauch your docker image in EC2

#Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess
```

### 3. Create ECR repo to store/save docker image

```bash
- Save the URI: 126391160164.dkr.ecr.ap-northeast-3.amazonaws.com/faceshape
```

### 4. Create EC2 machine (Ubuntu)

### 5. Open EC2 and Install docker in EC2 Machine:

```bash
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
```

### 6. Configure EC2 as self-hosted runner:

```bash
setting>actions>runner>new self hosted runner> choose os> then run command one by one
```

### 7. Setup github secrets:

```bash
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app
```

Feel free to contribute and make our vehicle insurance fraud detection project even better! 🚀👩‍💻
