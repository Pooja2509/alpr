# alpr
automatic license plate recognition
Worked on developing an ALPR system to detect, segment, and recognize license plates. 
Image Processing: Reduced noise and improved image clarity using adaptive histogram equalization. Corrected tilted plates with affine transformation.

Method
Detect License Plate
Perform segmentation of characters
Train a ML model to predict characters
Prediction of characters in License Plate


Setup
Clone the repository. Change the path of the image/video file in DetectPlate.py Run PredictCharacters.py. This will load the trained model (finalized_model.sav) which is added to repo for reference. Your own model can also be trained using the dataset attached in repo. Running PredictCharacters.py first gives grayscale and binary image. Then produces gray image with license plate bounded inside a rectangle. Each characters are also segmented and shown within boxes. Finally the model predicts the license plate.

