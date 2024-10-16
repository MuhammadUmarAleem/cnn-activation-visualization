# CNN Activation Visualization

This repository contains a Jupyter notebook that visualizes the activation maps of a Convolutional Neural Network (CNN) layer. The notebook demonstrates how to import an image, apply convolutional filters, and visualize the resulting activation maps.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/cnn-activation-visualization.git
    cd cnn-activation-visualization
    ```

2. Create and activate a new environment:
    - __Linux/Mac__:
        ```sh
        conda env create -f requirements/dog-linux.yml
        source activate dog-project
        ```
    - __Windows__:
        ```sh
        conda env create -f requirements/dog-windows.yml
        activate dog-project
        ```

3. Install the required packages:
    ```sh
    pip install -r requirements/requirements.txt
    ```

4. (Optional) If you are using AWS, install TensorFlow with GPU support:
    ```sh
    sudo python3 -m pip install -r requirements/requirements-gpu.txt
    ```

5. Switch Keras backend to TensorFlow:
    - __Linux/Mac__:
        ```sh
        KERAS_BACKEND=tensorflow python -c "from keras import backend"
        ```
    - __Windows__:
        ```sh
        set KERAS_BACKEND=tensorflow
        python -c "from keras import backend"
        ```

6. (Optional) Create an IPython kernel for the `dog-project` environment:
    ```sh
    python -m ipykernel install --user --name dog-project --display-name "dog-project"
    ```

## Usage

1. Launch Jupyter notebook:
    ```sh
    jupyter notebook
    ```

2. Open the [conv_visualization.ipynb](http://_vscodecontentref_/1) notebook and run the cells to visualize the activation maps.