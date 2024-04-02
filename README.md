# Mnist_quickdraw
The training script of MNIST &amp; tflite model
## 1. First step
### 1. Install virtual env
- If you haven't installed [NuEdgeWise](https://github.com/OpenNuvoton/NuEdgeWise), please follow these steps to install Python virtual environment and ***choose `NuEdgeWise_env`***.
- Skip if you have already done it, or you may pip install the needed python libs youself.
### 2. Running
- The `NVT_MNIST.ipynb` notebook will help you pre-process the data, train the model, and finally convert it to a TFLite.

## 2. Work Flow
### 1. Dataset
- The dataset is install from tf.dataset API or [mnist-c](https://github.com/google-research/mnist-c?tab=readme-ov-file)
### 2. Training
- Follow the `NVT_MNIST.ipynb` notebook
### 3. Test & Deployment
- Use [NuEdgeWise](https://github.com/OpenNuvoton/NuEdgeWise)'s [ML_Image_Classification](https://github.com/OpenNuvoton/ML_Image_Classification/tree/master/vela) to convert to TFLite and C++ files.

## 3. Inference code
- MCU: M460, M55M1 
