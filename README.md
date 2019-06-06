# Dog Breed classifier using CNN
We design a dog breed classifier using a convolutional neural network (CNN). We first design a dog classifier from scratch and later show that the accuracy of classification is significantly bumped up by using transfer learning based on a pre-trained model on a large set of varied images (including dogs). Finally, we put together various pieces to produce an app that firstly detects if the image is of a human or a dog or none. Then if a dog is detected, it would predict the breed of the dog or else if a human is detected, it tells the closest dog breed resembling the human

## Documentation

### Theory
---
The implementation uses the VGG16 pre-trained model ([VGG16](https://keras.io/applications/#vgg16))

### Installation
---
* Install jupyter notebook to open the main file. For new users, its recommended to install Anaconda from [here](http://docs.anaconda.com/anaconda/install/)
* Navigate to the specific folder and clone the repository using the following command:
    ```
    git clone https://github.com/jsarneja/dog_breed_classifier_using_CNN.git
    ```
* Open the jupyter notebook `dog_app.ipynb`
    * Some additional datasets would be needed. Relevant links are provided in the jupyter notebook

## Contributing
---
We love pull requests from everyone. Here are some ways you can contribute:
* by reporting bugs
* by suggesting new features
* by writing or editing documentation
* by closing [issues](https://github.com/jsarneja/dog_breed_classifier_using_CNN/issues)