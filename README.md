# Image-Segmentation-Pets-Datset
Image segmentation task for IIIT-Oxford Pets Dataset. Develops and compares various segmentation architectures with vanilla and pre-trained encoder backbones. Also introduces important utility functions.

Experiment 1-
Analyses the effect of resizing images of varying resolution in a dataset to a common value.

Introducing function called block_tiles that creates patches of user defined resolution from a large image
![Part 1](https://github.com/Khalid-Rafiq-01/Image-Segmentation-Pets-Datset/blob/main/Images/Screenshot%20(17).png)

Removing Images that contain a lot of sparse information(percentage of background pixels in a patch)
![part 2](https://github.com/Khalid-Rafiq-01/Image-Segmentation-Pets-Datset/blob/main/Images/Screenshot%20(18).png)

Introducing a finction called reassemble that reassembles patches of predicted masks back into the original large mask.
![Part 3](https://github.com/Khalid-Rafiq-01/Image-Segmentation-Pets-Datset/blob/main/Images/Screenshot%20(19).png)
