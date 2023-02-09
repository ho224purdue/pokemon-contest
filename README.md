# pokemon-contest
Computer Vision Project that was originally intended as a submission for the Purdue SIGAI Pokemon Classification contest. Ended up working and updating it continuously over the course of Fall semester. The software included within this project include deep learning neural network models that can be trained through the usage of convolutional neural networks and residual neural networks. Libraries utilized include Keras, Scikit-learn and Pytorch. 

# Convolutional Neural Networks in Computer Vision
A convolutional neural network (CNN) is a type of artificial neural network used primarily for image and video recognition tasks. It consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers. The convolutional layers apply a convolution operation on the input image to extract local features. The pooling layers reduce the spatial size of the feature maps, which helps to reduce computational cost and avoid overfitting. The fully connected layers learn a non-linear function to make the final predictions. CNNs use weight sharing, where the same filters are applied across different parts of the image, and parameter sharing, where the same parameters are used in different neurons of the same layer, which greatly reduces the number of parameters compared to fully connected networks. This makes CNNs highly suitable for image and video recognition tasks where the spatial structure of the data is important.

#Residual Neural Networks
A residual neural network (ResNet) is a type of deep neural network that addresses the vanishing and exploding gradient problem in traditional deep neural networks by introducing the concept of residual connections. In a ResNet, instead of directly learning the mapping from inputs to outputs, the network learns to add a residual mapping to the input to produce the output. This allows for deeper networks to be trained without suffering from degradation in performance, which can occur in traditional deep networks due to the difficulty of learning the identity function. ResNets are widely used in computer vision and image classification tasks, where they have achieved state-of-the-art performance on many benchmarks. They can also be applied to a wide range of other tasks and domains, such as speech recognition and natural language processing.

# Usage
Each software file should be able to recognize the directory from the extracted zip file 'pokemon-contest' which contains all the images that can be used to train the model. To work with the repository, download the images file and place them within a directory called 'pokemon-contest'. Then place the software files containing the models on the same level as the 'pokemon-contest' directory containing the images.

##Resources
The information below are some of the resources that were provided during the classification contest that took place at Purdue SIGAI

### Song requests:
https://docs.google.com/spreadsheets/d/1meCOevcCKUXD1g5oSq21gmGNW8e0tSlGvm8vW_AI68s/edit#gid=0

### Link to slides:
https://docs.google.com/presentation/d/1G4cHmYhWwOG6HTHH56GmynfVHD1W0-ZFyjkZMDWZkmc/edit#slide=id.p

## Some helpful resources

### Links to help host it on Google Drive:
- (https://towardsdatascience.com/pro-tip-for-downloading-custom-datasets-in-colab-environment-5413896d14ec) - download zipped file and upload to Drive
- (https://www.vsaytech.com/deep-learning/google-drive-google-colab-github-dont-just-read-do-it/) - mount Drive to Colab, clone repo, and more
- (https://bebi103a.github.io/lessons/02/git_with_colab.html) - open a repo on Colab

### Links to load the dataset:
- (https://www.tensorflow.org/tutorials/load_data/pandas_dataframe) - load a pandas dataframe as a dataset
- (https://www.tensorflow.org/tutorials/load_data/images) - load a dataset and preprocess images

### Links for preprocessing help:
- (https://www.tensorflow.org/api_docs/python/tf/image/) - contains documentation on most, if not all the methods you'll use for preprocessing

### Links to help build an image classification neural network:
- (https://www.tensorflow.org/tutorials/images/cnn) - TensorFlow documentation for building a CNN
- (https://medium.com/m2mtechconnect/classifying-pok%C3%A9mon-images-with-machine-learning-79b9bc07c080) - Medium article that walks you through building a Pokemon classifier (not good enough to win, though!)
