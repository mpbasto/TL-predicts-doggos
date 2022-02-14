# Using Transfer Learning and TensorFlow 2.0 to Classify Different Dog Breeds 🐕

In this project, I used machine learning and data from [Kaggle's Dog Breed Identification Competition](https://www.kaggle.com/c/dog-breed-identification/data) to help identify different breeds of dogs. This kind of problem is called multi-class image classification, as there are mutliple different breeds of dog.

The model used is one pretrained in the domain of image classification from [TensorFlow Hub](https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/4). It makes predictions with **MobileNet-V2**, a convolutional neural network that is 53 layers deep and a very effective feature extractor for object detection and segmentation.

Even though there are many ways of building a model in TensorFlow, bone of the best ways if one is getting started is to use the [Keras API's Sequential model](https://www.tensorflow.org/guide/keras/sequential_model).

<img src="https://miro.medium.com/max/1400/1*vkQ0hXDaQv57sALXAJquxA.jpeg"
     alt="Convolutional Neural Networks diagram"
     style="height: 200px; width: 500px;"
     align="right"/>
 
### *Convolutional Neural Networks*

 There are a few articles worth reading, but this one by Sumit Saha was definitely my go-to when I was researching Convolutional Neural Networks:
 https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53. 
 
 Sumit is a data scientist and machine learning engineer who can do some technical blogging too.
