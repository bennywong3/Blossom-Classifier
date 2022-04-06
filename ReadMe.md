# Cherry, Peach, Plum Blossom Classifier

For details of the project, please read Final-Report.pdf.
## Project Objectives
In spring, we often see people take photos with flowers. However, do they really know what
flower they are taking pictures with? Can you distinguish blossoms at the front page? Probably
not. Lots of flowers are very alike, especially cherry blossoms, plum blossoms and peach
blossoms. Therefore, we are going to build an application to identify these flowers.
## Application Description
We are interested in classifying different types of flower objects with a similar appearance. In
particular, blossoms of cherry, plum and peach are hard to distinguish for human beings.
Therefore, we would like to have an AI to learn to make decisions and differentiate for us. Users
can input photos with flowers of one of these three types to our application for classification.
Highlight of the work
1. We constructed a dataset using 618 images with data
augmentation from website Pixabay.
2. Convolutional Neural Networks (CNNs) are used for building the
image processing and classification model. Besides building our
own CNNs, we used transfer learning on ResNet, VGG19 and
Inception V3 to analyze model performance.
3. We identified that the dataset and model complexity are the
major constraints in affecting the performance of our model.
Although due to limitations we have not completely implemented
the solutions yet, we propose some ways in the report for further
improvement.
## Introduction Video
[![Watch the video](https://img.youtube.com/vi/pPT-jrxJrn4/maxresdefault.jpg)](https://youtu.be/pPT-jrxJrn4)

## How to use
Please upload the whole file "Blossom-Classifier" to Google Drive and the file should be under My Drive.
The directory should be /content/drive/My Drive/Blossom-Classifier/

To predict blossom images, please put your images in the folder images. 
We have provided 6 sample images inside. Feel free to replace them.

Other operating instructions are inside the "group5_final_version.ipynb" file. Please run the file using Google Colab.

Backup Link:
https://drive.google.com/drive/folders/1O5I3smX6MRYadqO782wDQD0g3Kmc7fcX?usp=sharing
https://colab.research.google.com/drive/1Pzw-EphTED_A5Kfs5s8PqaTOvQulDeol?usp=sharing
