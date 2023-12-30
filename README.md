The goal of this project is to classify images of humans and dogs using different Convolutional Neural Netorks. If the given image is a dog, the breed is guessed, 
if it's a human, a dog breed that resembles the human image is returned instead.

**File Descriprion**
 - requirements.txt - contains the list of neccessary python libraries to run following notebooks
 - dog_app.ipynb - code used in the project
 - images - folder that containts images for testing the models

**Results**
3 models were tested, their test-accuracies were the following:
- scracth:  6.1298 %
- VGG-19:   43.3014 %
- ResNet-50:81.2201 %

**Acknowledgements, data**
OpenCV face detector: https://github.com/opencv/opencv/tree/master/data/haarcascades
ResNet-50 model: https://ethereon.github.io/netscope/#/gist/db945b393d40bfa26006
ImageNet data: https://www.image-net.org/