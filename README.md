# Deep_Learning_Driver_Recognition
A deep learning project inspired from the Kaggle competition: "Distracted Driver Detection"

This repository contains a notebook 'Driver_Recognition.ipynb' in which different deep learning developpments are implemented 
in order to detect 10 classes of driver behaviors. The presentation of the problem and the construction of the data sets are 
described in the notebook itself. The notebook is composed of four parts:

-  Part 1: Data treatment
-  Part 2: Construction of a naive Convolutional Neural Network with **TensorFlow**
-  Part 3: Dimension reduction: an Iterative Principal Component Analysis method
-  Part 4: Construction of a deep Residual Network with **Keras**

In order to build the data sets you will first need to download 20000 .jpeg images zipped in the **imgs.zip** file available on the Kaggle website. Follow this link __[https://www.kaggle.com/c/state-farm-distracted-driver-detection/data](https://www.kaggle.com/c/state-farm-distracted-driver-detection/data)__ and click on the `Download All` button. Then unzip **imgs.zip**. You should obtain a `train` folder which contains all the .jpeg images. Note that in the notebook, the path towards this folder `./train/` is required to build the dataset.
