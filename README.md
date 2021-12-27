<div id="top"></div>

<h3 align="center">CNN and Hyperparameter</h3>

  <p align="center">
    This was an assignment I took in the deep learning course at KFUPM (ICS471) at term 211.
    <br />
    <a href="https://github.com/ahmadxcix/CNN-and-Hyperparameter"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ahmadxcix/CNN-and-Hyperparameter">View Demo</a>
    ·
    <a href="https://github.com/ahmadxcix/CNN-and-Hyperparameter/issues">Report Bug</a>
    ·
    <a href="https://github.com/ahmadxcix/CNN-and-Hyperparameter/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>




## About The Project

Face recognition can be categorized into face classification and face verification. Given an image of a person’s face, the task of classifying the ID of the face is known as face classification, which is a closed-set problem. The task of determining whether two face images are of the same person is known as face verification, which is an open-set problem1.
  I used Convolutional Neural Networks (CNNs) to design an end-to-end system for face classification/identification. The system will be given an image as input and will output the ID/name of the person shown in that image.
I trained a model on a dataset with a few hundreds images of labeled ID’s (i.e., a set of images, each labeled by an ID that uniquely identifies the person). I Used Jupyter notebook to show each of the following steps:
* a required model from the assignment's file which I implmented and fine tune different optimizers.
* a changed model from the orignal one, and comparing the two
* a transfer learning model with VGG-16 model

I implmented also early stopping technique, which look at the best validation loss and save the model.



### Built With

* [PyTorch](https://pytorch.org/)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/)






<!-- GETTING STARTED -->
## Getting Started

Download the dataset of and adjust the path to `classification_data` which has 3 folders; `test_data`, `train_data`, and `val_data`. 



