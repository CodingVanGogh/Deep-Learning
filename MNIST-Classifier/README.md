# MNIST Classifier with Keras and TensorBoard
---
## Abstract
This piece of code, builds and trains a Convolutional neural network to classify hand-written digits using the MNIST dataset. The code uses python3, keras and tensorboard.

## Dependencies
* Jupyter Notebook
* Python dependencies are listed in requirements.txt

## Steps to run the code
* Make sure all the dependencies are installed
* Open the MNIST-Classifier.ipynb notebook using a jupyter notebook
* Run all the cells in the notebook
* Logs are written into the directory named logs
* Start tensorboard from the same directory as the notebook using the command : tensorboard --logdir logs
* Open http://<HOST IP>:6006 on a new tab to open tensorboard dashboard
* Wait for about 10 minutes if you are training on a CPU
* The model and the learned weights are written to 'mnist_model.json' and 'model.h5' respectively
* Confirm that the accuracy of the model on the validation set approximately 99%
    