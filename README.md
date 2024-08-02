# Image-Caption-Generator using Machine Learning using CNN and LSTM
Image Captioning is a task where each image must be understood properly and are able 
generate suitable caption with proper grammatical structure. Here it is a hybrid system which 
uses multilayer CNN (Convolutional Neural Network) for generating keywords which narrates 
given input images and Long Short Term Memory(LSTM) for precisely constructing the 
significant captions utilizing the obtained words .Convolution Neural Network (CNN) proven 
to be so effective that there is a way to get to any kind of estimating problem that includes 
image data as input. LSTM was developed to avoid the poor predictive problem which occurred 
while using traditional approaches. We used an encoder-decoder based model that is capable 
of generating grammatically correct captions for images. This model makes use of 
VGG16(Visual Geometry Group) as an encoder and LSTM as a decoder. The model will be 
trained like when an image is given model produces captions that almost describe the image. 
The efficiency is demonstrated for the given model using Flickr8K data sets which contains 
8000 images and captions for each image but we use CNN and LSTM to capture dependencies 
and tell both the spatial relationships of images and contextual information of captions and 
generate contextually relevant captions. 
