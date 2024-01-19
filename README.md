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
export MLFLOW_TRACKING_URI=https://dagshub.com/RagalahariAkula-42/vehicle_insurance_fraud_detection.mlflow
export MLFLOW_TRACKING_USERNAME=RagalahariAkula-42
export MLFLOW_TRACKING_PASSWORD=7ca8771510f6ceac31f9f0fa87bdace49455316c
```
## About MLflow
MLflow ensures production-grade model tracking.
Log and tag your models for effective monitoring.

## Render
Render is a cloud platform that provides hosting and services for web applications. Render offers a user-friendly dashboard where users can manage various aspects of their applications and infrastructure.

[https://vifd.onrender.com](https://vifd.onrender.com)

Feel free to contribute and make our vehicle insurance fraud detection project even better! 🚀👩‍💻