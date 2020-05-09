Building complex model on Pytorch using Transfer Learning that is able to classify complex images. 

What is Transfer Learning?

Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example, knowledge gained while learning to recognize cars could apply when trying to recognize trucks.

In this project I have used Transfer Learning technique to classify complex images.

The model I used here is award wining vgg16 model with 13 convolutional layers for feature extraction and 3 fully connected layers for classification. The accuracy this model yield is around 91% which is amazing considering that the dataset I used is small, by increasing the size of dataset, much better accuracy can be achieved.
I would recommend to use your own dataset and just use my model as a reference.



requirements:-

pip install torch===1.5.0 torchvision===0.6.0 -f https://download.pytorch.org/whl/torch_stable.html