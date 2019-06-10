Description
===========
This is project RNNs for Visual Question Answering developed by team 1926-inf composed of Sen Fu, Zhen Liang, Xianze Meng, Yupei Zhu
Requirements
============
torch
tqdm
h5py
nltk
glove.6B.300d.txt (http://nlp.stanford.edu/data/glove.6B.zip)
=================
Demo.ipynb -- Run a demo of our code (reproduces all the figures of our report)
Experiment.ipynb -- Run the training of our model
Preprocessing.ipynb -- Run the pretraining (needed for training but unnecessary for demo)
pre/voca.json -- pretrained dictionary for answers and questions of VQA v2
pre/voca_v1.json -- pretrained dictionary for answers and questions of VQA v1
VQA1_EMB/ -- Model with pretrained Embedding layer with VQA v1
VQA2_EMB/ -- Model with pretrained Embedding layer with VQA v2
VQA2_CONV/ -- Model with pretrained Embedding layer and convolution layers have 3x3 kernel with VQA v2
VQA1_GRU/ -- Model with pretrained Embedding layer and LSTM layers are replaced by GRU with VQA v1
VQA2_GRU/ -- Model with pretrained Embedding layer and LSTM layers are replaced by GRU with VQA v2
