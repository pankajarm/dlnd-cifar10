# dlnd-cifar10

![alt tag](http://karpathy.github.io/assets/cifar_preview.png)

In this project, we will classify images from the CIFAR-10 dataset.

The dataset consists of airplanes, dogs, cats, and other objects. The dataset will need to be preprocessed, then train a convolutional neural network on all the samples.

We will normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, we will see their predictions on the sample images.

### Install
I am using [Conda](https://www.continuum.io/anaconda-overview) to install TensorFlow. You might already have a TensorFlow environment, but please check below to make sure you have all the necessary packages. If you have never used Conda environments before, please go through my other tutorial [What is Anaconda and Why should I bother about it?](http://pankajmathur.com/what-is-anaconda-and-why-should-i-bother-about-it/)

Assuming you have conda install on your machine, plesae run the following commands to have tensorflow-playground ready for you to play.

### OS X or Linux
Run the following commands to setup your environment:

```
conda create -n tensorflow-playground python=3.5
source activate tensorflow-playground
conda install pandas matplotlib jupyter notebook scipy scikit-learn
pip install tensorflow
```

### Windows
And installing on Windows. In your console or Anaconda shell:

```
conda create -n tensorflow-playground python=3.5
activate tensorflow-playground
conda install pandas matplotlib jupyter notebook scipy scikit-learn
pip install tensorflow
```
After creating conda environment, clone [this repository](https://github.com/pankymathur/tensorflow-playground) on your local machine via Git or [GitHub Desktop](https://desktop.github.com)

under tensorflow-playground environment on your terminal or shell window, cd to cloned directory and then run following command:

```
jupyter notebook
```
