# Project Description (From Canvas)

With current astronomical surveys the number of detected sources is already large and with future telescopes the volume of data will become huge, 
so that Machine Learning techniques will be required to seek out the interesting objects. Machine Learning is a rapidly expanding part of astronomy (and science 
in general) and this project will equip the student with a number of useful skills. This project will look at different angles of Machine Learning, A key
component of using Neural Networks to find objects in survey data (eg using Image Recognition) is the training set required to effectively train the Neural Network. 
These training sets can be generated in a number of ways and we will explore some different approaches. One approach will be to use a Generative Adversarial
Network (GAN) to generate synthetic images of the objects of interest (for instance, radio galaxies, non-thermal filaments, bow-shocks or  supernova remnants), 
which we can then use to train a neural network to search for these objects in a specific survey, such as the MEERKAT Galactic Plane Survey or the SPITZER GLIMPSE
survey. Another approach is to use analytic approaches to model radio galaxies or other objects of interest. Having generated synthetic training sets we will then apply 
them to search the survey data to look for objects in the different classes. We can then identify new sources of interest.



## Pre-processing
Input(s):
.fits files

Outputs(s):
.jpg files



## GAN Construction
Infrastructure: TensorFlow and Keras
Input(s):
.jpg files

### Further Prospects (Will be looked into in semester 2 with BluBear):
1. StyleGAN
2. Use MeerKAT images (see repository)
- (Note: BluBear account has been made and jobs are in queue to be uploaded. Awaiting maintenance run end on 14th December)
