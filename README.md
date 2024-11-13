# Image Classification using Pytorch 

This project is a machine learning application using PyTorch, torchvision, and Kaggle datasets. 
The notebook includes data preparation, model training, and evaluation.

## Setup Instructions

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Kaggle API for dataset access

### Installation

1. Clone this repository and navigate to the project directory:

    ```bash
    git clone <https://github.com/Vaishnavi-mocherla/ImageClassifier-PyTorch>
    cd <ImageClassifier-PyTorch>
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Kaggle API Setup

1. Download your Kaggle API token (`kaggle.json`) from [Kaggle Account](https://www.kaggle.com/account).
2. Place the `kaggle.json` file in the root of the project folder.
3. Run the following commands in your notebook or terminal:

    ```python
    import os
    os.system('mkdir -p ~/.kaggle')
    os.system('cp kaggle.json ~/.kaggle/')
    os.system('chmod 600 ~/.kaggle/kaggle.json')
    ```

### Usage

Open the Jupyter Notebook and run all cells to train the model and evaluate it.
Ensure your Kaggle setup is complete before accessing datasets.

### Files
- **code-file.ipynb**: The main notebook for the machine learning task.
- **kaggle.json**: Your Kaggle API token (not included in the repository; see setup instructions).
- **requirements.txt**: Python package dependencies.
- **.gitignore**: Excludes unnecessary files from the repository.


