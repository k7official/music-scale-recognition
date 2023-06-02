### Music Scale Recognition Using Mel-ceptstrum

In this competition, you are required to recognize the scales (音階) of musical sounds. By some sound signal processing method, each sound sample has been converted into the mel-cepstrum feature, which can be represented as a 2-D image. Using this image, you need to build a CNN model to recognize it into a music scale.

### How to Retrieve the Dataset for Model Training?

You can get one image dataset of the extracted mel-cepstrum features from http://web.csie.ndhu.edu.tw/ccchiang/Data/music_train.zip for training your model. Associated with the dataset, you are given an annotation file http://web.csie.ndhu.edu.tw/ccchiang/Data/truth.txt which contains the label of each training image. Each line in this file has two fields, i.e., the image filename and the label of this image which is a number ranging between 0 and 87.

### Testing

To test your network model, here is the test dataset (http://web.csie.ndhu.edu.tw/ccchiang/Data/music_test.zip. All you need to do is to use your trained CNN to recognize the images in this dataset. You have to output the recognized scale for each testing image and prepare the outputs as an 'output.csv' file according to the required format for submission to Kaggle.

Competition link: https://www.kaggle.com/competitions/music-note-recognition-by-cnn/overview/description
