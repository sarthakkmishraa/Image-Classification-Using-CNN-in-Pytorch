# Image-Classification-Using-CNN-in-Pytorch

The aim of this project is to predict the label of the object, i.e., image classification on the given images dataset using **Convolutional Neural Networks(CNN)** in **Pytorch**.

The dataset used is **CIFAR-10 dataset** which is a subset of the **80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class**. 

The **CIFAR-10** data consists of **60,000 32x32 color images in 10 classes, with 6000 images per class. There are 50,000 training images and 10,000 test images in the official data**. We have preserved the train/test split from the original dataset.  The provided files are:

**1.train.7z** - a folder containing the training images in png format

**2.test.7z** - a folder containing the test images in png format

**3.trainLabels.csv** - the training labels

The label classes with their respective indices in the dataset are:

**0-> airplane**

**1-> automobile** 

**2-> bird**

**3-> cat**

**4-> deer** 

**5-> dog** 

**6-> frog** 

**7-> horse** 

**8-> ship** 

**9-> truck**

**PyTorch** is an open source machine learning library based on the Torch library, used for applications such as **computer vision and natural language processing**, primarily developed by **Facebook's AI Research lab**. It is a **free and open-source software** released under the Modified BSD license.


The dataset has been split into **train,test and validation datasets**. The training set consists of **45,000 images** while the validation set consists of **5000 images**. The test set contains the **remaining 10,000 images**. The **CNN model** was trained on the training dataset for **10 epochs** with a learning rate of **0.001** and kernel size of **3x3 2D Convolution filter** matrix. On the top of it, **MaxPool2d** layer was applied and the output was **flattened out to vector**. Images were passed as **Pytorch Tensors** to the model. After training, the model achieved **78% Accuracy** which is a reasonable score. The accuracy can be further improved by **changing the learning rate**, **adding more layers** and **applying regularization techniques.**

