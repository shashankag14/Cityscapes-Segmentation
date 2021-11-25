# Semantic Segmentation on Cityscapes Dataset

In an era of various devices rapidly getting dependent on the vision systems to see and interpret the world around them, detection and segmentation techniques have played an indispensable role by teaching these devices on how to decipher the world around them. In this project, we have implemented Recurrent Residual Neural Network based on U-Net model (R2-Unet) proposed by Alom et. al. for semantic segmentation on Cityscapes dataset. In addition to that we have
proposed four different modifications to the R2U-Net architecture and compared their relative performances. Finally, the best modification of increasing model depth shows an improved detection of classes that were less frequently observed in the dataset.

The below image shows the comparison of model output between R2UNET and modified R2UNET on unseen images. First row shows the original images. Second row shows the predicted segmentation labels of R2U-Net model. Third row shows the predicted segmentation labels of modified R2U-Net.

![image](https://user-images.githubusercontent.com/74488693/143465509-149232a8-a64c-4249-93af-ca6dc8abda49.png)

