# Introduction to Convolutional Neural Networks (CNN)
A fast introduction to neural networks and CNN:s will be given. Then we will go through a short example where we use CNN:s to classify images.  

Files will be available at the day of the conference. 

## Prerequisites
1. [Install Python 3.6.5 +](https://www.python.org/downloads/)
2. [Install python virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)
3. Clone project, create virtual environment and install jupyter notebooks  
```
# Example windows 

git clone https://github.com/wave-consulting/CNN_Image_Recognition.git

cd CNN_Image_Recognition

virtualenv venv

venv\Scripts\activate

pip install -r requirements.txt
```
4. Get ready to do some machine learning magic.

## Using tensorflow with GPU

If you are planning on using tensorflow with GPU instead of CPU then you need to install CUDA and related packages. 

Guide is available at 
https://www.tensorflow.org/install/gpu

The package you will be using is  

```
pip install tensorflow-gpu
```

System requirements (Stable version 1.14):
* NVIDIA® GPU drivers — CUDA 10.0 requires 410.x or higher.
* CUDA® Toolkit — TensorFlow supports CUDA 10.0 (TensorFlow >= 1.13.0)
* CUPTI - ships with the CUDA Toolkit.
* cuDNN - SDK (>= 7.4.1)
* (Optional) TensorRT 5.0 - to improve latency and throughput for inference on some models.
