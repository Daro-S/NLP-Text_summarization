# End to end Text-Summarizer-Project

This is project is build from scratch with the purpose of implementing and learning the workflow of data science research by using modular structures. This project is aim to sharp my skills in:

- Python
- Project Structure
- Clean Code
- Documentation
- Project Flow
- Fast API
- Pytorch
- Data version control
  ...etc..
  I also aim to integrate MLflow but my PC does not support GPU so I decided not to integrate.

# Activate VENV

```bash
.\vtextSummarization\Scripts\activate
```

# To run Fast API

```bash
python app.py
```

then open your browser and run this:

```bash
http://localhost:8080/docs
```

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py

# DVC - Data Version Control

1. dvc init
2. dvc repro
3. dvc dag (to see the structure of the pipeline)
