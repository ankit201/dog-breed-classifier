# Dog-breed-classifier

The motivation behind this project is to utilize a convolutional neural system (CNN) to anticipate hound breeds. The pipeline is the assessment of a picture as a dog or a human, at that point a forecast of which dog variety the dog is, or which canine variety the human most takes after. On the off chance that the picture is distinguished as neither a dog nor a human, the classifier won't run.

## Files included:

##### dog-app.ipynb is the python 3 file that can be run to classify dog images

## Downloads: 
### Pre-computer bottleneck features for InceptionV3
https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz

## Project Results:
In summary, the performance of the pre-trained model I built far exceeded the hand made CNN model. The accuracy of the InceptionV3 model (pre-trained on ImageNet) reached 80% while my CNN was about 4%.  This improved performance can be attributed to the vast dataset on which the pre-trained model was built.  In particular, the pre-trained model was also exposed to many dog images, making it particularly ready to classify dog breeds.

Link to Medium story here: 
