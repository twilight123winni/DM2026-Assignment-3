# NYCU Data Mining(Spring 2026) Assignment 3

## Environment

This project is implemented in Python using Jupyter Notebook (`.ipynb`).

Required packages:

```bash
pip install pandas numpy tqdm matplotlib scipy scikit-learn lightgbm glob
```


## Dataset Structure

Please place the dataset under the following structure:

```text
data/
├── train/
│   └── train/
│       └── User_*/
│           └── *.csv
├── test/
│   └── test/
│       └── User_*/
│           └── *.csv
```

## Path Configuration

Before running the notebook locally, you can modify the following section to your local dataset directory if needed:

```python
if os.path.exists('/kaggle/input'):
    BASE_PATH = '/kaggle/input/datasets/yyc023/2026-dm-assignment3'
else:
    # *** Change PATH here***
    BASE_PATH = './data'
```

Example:

```python
BASE_PATH = 'D:/dataset/2026-dm-assignment3'
```



## How to Run

Open the notebook and run all cells sequentially.


## Output

The generated prediction file will be saved automatically as:

```text
submission.csv
```


## Notes

* The notebook is designed to run end-to-end without additional scripts.
* Random seed is fixed for reproducibility.
