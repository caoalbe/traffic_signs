# traffic_signs
We train a YOLO (You Only Look Once) model to detect traffic signs in real time, and also perform data analysis.

We use the [Traffic Signs Dataset in YOLO format](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-dataset-in-yolo-format) dataset from Kaggle, created by [Valentyn Sichkar](https://www.kaggle.com/valentynsichkar/datasets).

## Requirements
- Python 3.11

## Installation
It is recommended to use a virtual environment to manage the necessary dependencies.

1. **Create virtual environment**
```bash
$ python -m venv venv
```

2. **Activate virtual environment**
- On macOS/Linux:
```bash
$ source venv/bin/activate
```

- On Windows:
```bash
$ venv\Scripts\activate
```

3. **Install dependencies**
```bash
$ pip install -r requirements.txt
```

4. **Deactivate virtual environment**
```bash
$ deactivate
```

## Run Notebook
You can run the notebook with the following:
```bash
$ source venv/bin/activate
$ jupyter notebook
```
