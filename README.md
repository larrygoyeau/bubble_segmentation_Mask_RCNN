# Bubble segmentation Mask RCNN

This framework allow you to segment bubbles on images. If you want to segment foam images from your device, run the notbook 'Mask_RCNN_automatic_segementation.ipynb' on colab, or simply open this link:
https://colab.research.google.com/github/larrygoyeau/bubble_segmentation_Mask_RCNN/blob/master/Mask_RCNN_automatic_segementation.ipynb

A window will open to select the images from your devise. After the automatic segmentation, you have the possibility to manually add and remove the missed bubbles.

If you want to see how was done the training prosess, open the notbook 'train_Mask_RCNN.ipynb', the code is adapted for colab.

The notbook 'Comparative_evaluation.ipynb' compare the performances of Mask_RCNN with Unet.

All the segmentation process is based on the framework 'Mask_RCNN' available here:
https://github.com/matterport/Mask_RCNN
