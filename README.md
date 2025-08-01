# RNN_practice
# Simple RNN Implementations in TensorFlow and PyTorch

This repository contains two basic Python scripts that demonstrate how to build and train a simple Recurrent Neural Network (RNN) using TensorFlow/Keras and PyTorch.

## Scripts

1.  `rnn_tensorflow_imdb.py`: Implements an RNN for sentiment analysis on the IMDB movie review dataset.
2.  `rnn_pytorch_mnist.py`: Implements an RNN for classifying MNIST digits by treating images as sequences of rows.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Create an environment and install packages:**
    ```bash
    # Create a conda environment
    conda create -n rnn_code python
    conda activate rnn_code

    # Install dependencies (for Apple Silicon M-series Mac)
    pip install tensorflow torch torchvision d2l==1.0.3
    ```
    *For non-Apple systems, install TensorFlow with `pip install tensorflow`.*

## Usage

Run the scripts from your terminal if you make yours in .py:

```bash
python rnn_tensorflow_imdb.py
```

```bash
python rnn_pytorch_mnist.py
```

Run the scripts from your Jupyter Notebook or VS Code after selecting the correct terminal if you make yours in .ipynb
