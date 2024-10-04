# FW24-AICUP

2024 Fall Winter AICUP team 5810

## Usage

```bash
conda create -n fw24-aicup python=3.10

conda activate fw24-aicup

pip install -r requirements.txt
```

### To execute the code

#### args

- `--folder_path`: training data folder path
- `is_valid`: whether to use validation data
- `--model_type`: model type

```bash
python -m src.main  --folder_path data --is_valid --model_type xgb
```


