# Melanoma Detection

In this project we tackle the question whether image classification performance can be improved when the noisy background surrounding the object of interest is removed. One approach is to use image segmentation to distinguish between background and the object of interest, then remove the background and use the resulting image as input to the classifier.
We use a skin lesion dataset to investigate this question. The skin lesions are classified into 7 classes, one of which is the cancerous melanoma class. Semantic segmentation with a U-Net architecture is used followed by image classification with the EfficientNetB5 architecture. Preceding classification with a semantic segmentation step improves performance on average by 2% measured on 8 different skin lesion test sets. 


![METHOD_FINAL](https://user-images.githubusercontent.com/96559466/156281405-8a80870a-5a4a-4623-b6f6-78e68a9865a1.jpg)
