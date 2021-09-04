# Face Detection (Phase 1)
Haar-like features are digital image features used in object recognition. They owe their name to their intuitive similarity with Haar wavelets and were used in the first real-time face detector. Paul Viola and Michael Jones in their paper titled “Rapid Object Detection using a Boosted Cascade of Simple Features” used the idea of Haar-feature classifier based on the Haar wavelets. This classifier is widely used for tasks like face detection in computer vision industry.
Face detection is performed by using classifiers. A classifier is essentially an algorithm that decides whether a given image is face (positive) or not a face(negative). A classifier needs to be trained on thousands of images with and without faces. But, OpenCV already has two pre-trained face detection classifiers, which can readily be used in a program. The two classifiers are: Haar Classifier and Local Binary Pattern(LBP) classifier. 
Here, We are using the Haar classifier.

Haar cascade files
OpenCV comes with a lot of pre-trained classifiers. For instance, there are classifiers for smile, eyes, face, etc. These come in the form of XML files and are located in the folder opencv/data/haarcascades/.
Download the XML files and place them in the data folder in the same working directory as the spyder notebook.
Following steps were followed
1. Load the necessary Libraries
2. Loading the image to be tested in grayscale
3. Loading the classifier for frontal face
4. call the function to detect faces
5. convert to RGB and display image






https://user-images.githubusercontent.com/89267839/132052847-96ecbe19-cc21-4c43-a896-56351972499a.mp4

Test on Image


![gayscale](https://user-images.githubusercontent.com/89267839/132081529-2d5e404c-de84-41f9-9df5-0c7c3f5b7524.png)
![output2](https://user-images.githubusercontent.com/89267839/132081579-8a922195-984c-4315-9a4c-d8434ae1ea5f.png)


Conclusion- Hence our model was able to detect faces fairly accurate.


# Face Mask Detection (Phase 2)
Since the inception of global pandemic of Novel Corona Virus Disease(coViD-19) many precautionary measures are made mandatory around the world. wearing of mask has been the most important one. monitoring this can be difficult, so what if an algorithm detects whether a person is wearing a mask or not?
This is what we are trying to implement. Here, we have used a dataset which is downloaded from Kaggle.
This dataset consists of 7553 images belonging to two classes:

with_mask: 3725 images
without_mask: 3828 images

# Detection
![ss3](https://user-images.githubusercontent.com/89267839/132084512-59729856-f1cc-467f-82ed-2cef2f2dca0c.png)


Our model gave 98% accuracy for Face Mask Detection after training
![accuracy](https://user-images.githubusercontent.com/89267839/132084476-1196458c-7a23-444b-ad54-cbcc1ef49ddd.JPG)



We got the following accuracy/loss training curve plot


![training loss](https://user-images.githubusercontent.com/89267839/132084419-736211d1-f7b6-4bbf-9a6d-ec2d79738650.JPG)





