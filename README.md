# Image-Segmentation-Pets-Datset
Image segmentation task for IIIT-Oxford Pets Dataset. Develops and compares various segmentation architectures with vanilla and pre-trained encoder backbones. Also introduces important utility functions.

Experiment 1-
Analyses the effect of resizing images of varying resolution in a dataset to a common value.

  APPROACH –
  
  Pre – Processing Step 1 
  
    Introduce functions that 
    
    Takes in patch size from the user.
    
    Crops the image to the largest integral value of patch size.
    
    Creates  integral number of patches from the cropped  image.
![Input Image](https://github.com/Khalid-Rafiq-01/Image-Segmentation-Pets-Datset/blob/main/Images/cat%201.png)

Using Function called block_tiles and inputting a user defined patch-size 

    
