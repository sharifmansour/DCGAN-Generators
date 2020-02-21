# DCGAN-Generators
 Exploring the Latent Space of DCGAN Generators.
 
The following code is meant to recreate the outcome from the original deep convolutional generative adversarial networks paper on their aim at exploring the latent space through arithmetic operations.

- Was run using tensorflow 2.0.0 and cuda 10.2. 
- Provided file should be fine to run on it's own and can be run easily through Spyder (Python 3.6).
- Please be mindful to update the folder path for the newly created images and training data. Begin by updating the folder location of the training data, then edit the location of the output images created. Output folder path found at line 580. Data folder path found at line 1085.
- To aid with initializing the cuDNN tensor graphs a simple LSUN bedrooms DCGAN model was included to test the architecture. I found this also help better understand the model. LSUN dataset can be found at the following URL: https://www.yf.io/p/lsun . Only the bedroom dataset was used but feel free to try other datasets if you like. Line 1010 is the folder location for LSUN dataset.
- Training data source will be provided for download.
- Data can be downloaded at: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
- Please download the align and cropped images.
- Also please make sure to download csv file indicating the attributes of the images.
- The attributes are important as you will be able to select the desired attributes for the creation of the images.
- In the code I've defaulted the attributes to be similar to that of the original DCGAN paper, however any attributes can be used.
- For now to use different attributes you'll need to manually update them in the correct locations in the code file.
- The rest of the attributes can be found here: https://towardsdatascience.com/celeba-attribute-prediction-and-clustering-with-keras-3d148063098d (Part of the code used to search the through the database can be found here. However, it was modified to suit the use case of the intended goal.)
- Default image resolution produced is 60x60 pixels, this however can be changed.
- Training time for 60x60 pixels is 60 hours. This is was run a on PC with the following specs: 
     - CPU:"i7-9750"
     - GPU:"NVIDIA GeForce RTX 2060"
     - RAM:"16GB"
- The following libraries will be needed to run the code:
     - "numpy"
     - "tensorflow"
     - "pandas"
     - "matplotlib.pyplot"
     - "tensorflow.keras.layers"
     - "os"
     - "tensorflow.python.framework"
     - "cv2" 
     - "time"
     - "numpy"
     - "PIL"
     - "mtcnn.mtcnn"
     ...
