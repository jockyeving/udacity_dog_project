The goal of this project is to classify images of humans and dogs using different Convolutional Neural Netorks. If the given image is a dog, the breed is guessed, 
if it's a human, a dog breed that resembles the human image is returned instead.

The blog post connected to this article can be read at: https://medium.com/@jockyeving/dog-breed-classification-using-convolutional-neural-networks-bd9005189104

**Instructions for the repository**
- To clone this repository, run:
  ```
  git clone https://github.com/jockyeving/udacity_dog_project.git
  ```
- create an anaconda enviroment:
  ```
  conda create --name dog-project python=3.9

  conda activate dog-project
  ```  
- install requirements (tested on Python 3.9):
  ```
  pip install -r requirements.txt
  ```

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
<br>OpenCV face detector: https://github.com/opencv/opencv/tree/master/data/haarcascades
<br>ResNet-50 model: https://ethereon.github.io/netscope/#/gist/db945b393d40bfa26006
<br>ImageNet data: https://www.image-net.org/
