## ML FLOW Experiments

import dagshub
dagshub.init(repo_owner='SwagathSuvaranRS', repo_name='mlflow_experiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


MLFLOW_TRACKING_URL=https://dagshub.com/SwagathSuvaranRS/mlflow_experiments.mlflow \
MLFLOW_TRACKING_USERNAME=SwagathSuvaranRS \
MLFLOW_TRACKING_PASSWORD=208dd0b60b1bbc589feb356f082cdf3e0ce9a2d0 \
python script.py


