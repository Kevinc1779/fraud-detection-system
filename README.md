# fraud-detection-system
fraud-detection-system/
  README.md
  requirements.txt

  data/
    raw/              # (gitignored) original dataset files
    processed/        # (gitignored) cleaned outputs

  notebooks/
    01_eda.ipynb
    02_feature_engineering.ipynb
    03_modeling.ipynb
    04_explainability.ipynb

  src/
    config.py
    data_prep.py
    features.py
    train.py
    evaluate.py

  models/
    fraud_model.pkl
    threshold.json

  api/
    main.py            # FastAPI app
    schemas.py         # request/response models
    predict.py         # loads model + predicts

  dashboard/
    app.py             # Streamlit app

  reports/
    figures/
    metrics.json
