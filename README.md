# Kidney-Disease-Classification-MLflow-DVC

### Workflows
* 1. Update config.yaml
* 2. Update secrets.yaml [Optional]
* 3. Update params.yaml
* 4. Update the entity
* 5. Update the configuration manager in src config
* 6. Update the components
* 7. Update the pipeline
* 8. Update the main.py
* 9. Update the dvc.yaml
* 10. app.py



### MLflow

#### cmd
* mlflow ui


#### dagshub
* MLFLOW_TRACKING_URI=https://dagshub.com/sujataroy2009/Kidney-Disease-Classification.mlflow
* MLFLOW_TRACKING_USERNAME=sujataroy2009
* MLFLOW_TRACKING_PASSWORD=your_token
* python script.py


#### Run this to export as env variables:

export MLFLOW_TRACKING_URI=https://dagshub.com/sujataroy2009/Kidney-Disease-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=sujataroy2009

export MLFLOW_TRACKING_PASSWORD=your_token
