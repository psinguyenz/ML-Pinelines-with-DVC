# Build & Track ML Pinelines with DVC

  +----------------+
  | data_ingestion |
  +----------------+
            *
            *
            *
+--------------------+
| data_preprocessing |
+--------------------+
            *
            *
            *
+---------------------+
| feature_engineering |
+---------------------+
            *
            *
            *
  +----------------+
  | model_building |
  +----------------+
            *
            *
            *
  +------------------+
  | model_evaluation |
  +------------------+

## How to run?

conda create -n test python=3.11 -y

conda activate test

pip install -r requirements.txt



## DVC Commands

git init

dvc init

dvc repro

dvc dag

dvc metrics show

