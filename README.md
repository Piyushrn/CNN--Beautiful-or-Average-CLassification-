# CNN--Beautiful-or-Average-CLassification-

Datset - https://www.kaggle.com/datasets/gpiosenka/beauty-detection-data-set


The data set consists of a training set, a test set, a validation set and a consolidated set. Each of these sets contains two folders labeled as Beautiful and Average.
For the training set there are 2000 images in the Beautiful folder and 2000 images in the Average folder. For the test set there are 150 images in the beautiful folder 
and 150 images in the Average folder. The validation set is similarly divided into 150 images of each type. The consolidated folder 2300 images in the Beautiful folder 
and 2300 images in the Average folder. The consolidated folder combines the images from the training, test and validation sets into a single set. This is convenient for 
users that want to create their own splits of training, test and validation images.



From my Observation, the images in the average folders have images with low pixels, clarity is not very good. Hence the model predicts average image if the image is
having low pixels.
