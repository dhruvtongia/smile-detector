# smile-detector

The above project uses the  Viola-Jones Face Detection Algorithm  (namely a cascade of boosted classifiers working with haar-like features)  
The current algorithm uses the following Haar-like features:
1) line features
2) edge features 
3) center - surround features

I have used the pre-trained haar cascades for frontal face , eyes ,and smile.
Used the OpenCV library to take real-time video from web cam and tried to draw as accuarte as possible , colored rectangles around the face , eyes and smile.

I also experimented with the different values of follwing two parameters of detectMultiScale()  :
1. <strong>minNeighbors</strong> – Parameter specifying how many neighbors each candidate rectangle should have to retain it.
2. <strong>scaleFactor</strong> – Parameter specifying how much the image size is reduced at each image scale.<br>
      for each of the haarcascades and found the most optimal ones.
    



