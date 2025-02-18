# Facial Mask Detection using Convolutional Neural Network
The wave of COVID-19 shook the whole world appearing as a threat to human existence in an era where science is about to solve every mystery unsolved; or at least, that’s what we thought. When modern science is yet to come up with that one remedy to shield us from the pandemic, a simple tool as layered masks are there to protect us efficiently for the time being as per the researches done in this regard. This work attempts to make sure that the tool is being used properly and hence it focuses on the detection of masks on mass people. Two Convolutional Neural Network (CNN) models were used in the work with two different sizes of datasets and the simulation with bigger datasets gave convincing output. With larger training data size of 22720 images, the test accuracy of CNN Model 1, CNN Model 2 and CNN Model 2 with transfer learning were respectively 99.571%, 99.857% and 99.928%.


## Dataset

The COVID Face Mask Detection Dataset from Kaggle (https://www.kaggle.com/datasets/prithwirajmitra/covid-face-mask-detection-dataset) was used at first to train and evaluate our models.Training data set size being 1685 here, gave good accuracy leaving some room for betterment. The test and validation datasets had sizes of 296 and 306 respectively.


As machine learning algorithms works better with larger, we combined two available datasets to make one dataset for our work. For unmasked human faces data, we have used Labeled Faces in the wild (LFW) dataset (https://www.kaggle.com/datasets/jessicali9530/lfw-dataset). This was created and maintained by researchers at the University of
Massachusetts,Amherst. This dataset has 13,233 imagesof 5,749 people collected from the web. The LFW dataset contains 11360 training data, 700 test data and 1900 validation data.


MaskedFace-Net (https://github.com/cabani/MaskedFace-Net) was used for masked human faces data. These masks were added artificially in the faces. The MaskedFace-Net dataset originally contained 137016 total image data but for keeping the comparison with LFW fair, this work used the same number of data (11,360) in each category as the LFW dataset. The 2 datasets were combined into 1 dataset in the study

