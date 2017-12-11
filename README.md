# Emotion recognition using Python 

## Acknowledgement:
This code uses the facial landmarks code available at  Adrian's website - link https://www.pyimagesearch.com/2017/04/17/real-time-facial-landmark-detection-opencv-python-dlib/. 

## How the code works??
The python code detects different landmarks on the face and predicts the emotions such as smile based on it. It automatically takes a photo of that person when he smiles. Also when the two eyebrows are lifted up, the system plays a music automatically and the music stops when you blink your right eye.

### Detecting Different facial expressions:
To detect smile in a face, points 49 and 50 are considered. The distance between those points increases when a person smiles and that is used here to detect a smile.

To detect left eye brow movement(lifting up), points 38 and 41 are considered. The distance between those points increases when a person smiles and that is used here to detect a smile.

Similarly to detect right eye brow movement(lifting up), points 44 and 47 are considered. The distance between those points increases when a person smiles and that is used here to detect a smile.




