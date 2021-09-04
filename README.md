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
![output img](https://user-images.githubusercontent.com/89267839/132081537-a66b98b8-5c02-4d22-b135-29208f444312.png)

Conclusion- Hence our model was able to detect faces fairly accurate.


# Phase 2


