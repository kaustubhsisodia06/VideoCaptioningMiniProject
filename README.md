
# VideoCaptioningMiniProject
Understanding visual media, i.e. images and videos, has been a cornerstone topic
in computer vision research for a long time. Recently, a new task within the
purview of this research area, that of automatically captioning images and videos,
has garnered wide-spread interest. The task involves generating a short natural
language description of an image or a video.
We will take a look at an interesting multi model topic where we will combine both image and text processing to build a useful Deep Learning application, aka Image Captioning. Image Captioning refers to the process of generating textual description from an image – based on the objects and actions in the image.

INTRODUCTION
This repository contains my implementation of a video captioning system. This system takes as input a video and generates a caption describing the event in the video.

I took inspiration from Sequence to Sequence -- Video to Text, a video captioning work proposed by researchers at the University of Texas, Austin.

REQUIREMENTS
For running my code and reproducing the results, the following packages need to be installed first. I have used Python 2.7 for the whole of this project.

Packages:

TensorFlow
Caffe
NumPy
cv2
imageio
scikit-image
