# DCGAN-Generators
 Exploring the Latent Space of DCGAN Generators.
 
The following code is meant to recreate the outcome from the original deep convolutional generative adversarial networks paper on their aim at exploring the latent space through arithmetic operations.

- Was run using tensorflow 2.0.0 and cuda 10.2. 
- Provided file should be fine to run on it's own and can be run easily through Spyder (Python 3.6).
- Please be mindful to update the folder path for the newly created images and training data. Begin by updating the folder location of the training data, then edit the location of the output images created.
- Training data source will be provided for download.
- Data can be downloaded at: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
- Please download the align and cropped images.
- Also please make sure to download csv file indicating the attributes of the images.
- The attributes are important as you will be able to select the desired attributes for the creation of the images.
- In the code I've defaulted the attributes to be similar to that of the original DCGAN paper, however any attributes can be used.
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
