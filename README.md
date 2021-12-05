# MNIST_KERAS
Install Anaconda-navigator
Install tensorflow and Keras bib
open Jupyter noebook
biblio import : 
import numpy as np
import matplotlib.pyplot as plt
from sklearn.metrics import confusion_matrix,classification_report
from keras.datasets import mnist
import scikitplot as skplt
from keras.models import Sequential,Model
from tensorflow.keras.layers import Input,InputLayer,Reshape,Conv2D, MaxPooling2D,Dense, Flatten 
from keras.layers.core import Dense,Dropout, Activation
from keras.utils import np_utils
