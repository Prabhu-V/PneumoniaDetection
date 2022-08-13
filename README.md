# Pneumonia Detection
Training classification model that can analyze the chest X-rays and help in the accurate diagnosis of Pneumonia

##### Dataset
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### Overview:
1.  Imported chest X-ray images, resized to 256*256 pixel size and flattened the images
2.  Fed into Autoencoder model for dimension reduction
3.  Trained SVM on dimensionally reduced data with RBF kernel
4.  Carried out image augmentation on X-ray images and trained CNN model on augmented data
5.  Used F1 Score as evaluation metric for early stopping

### Architecture:
##### AutoEncoder
![nndig](https://user-images.githubusercontent.com/108232437/184506980-6cc6fd8f-6b9a-4ecc-8def-294ab9909b94.jpg)

##### CNN
<img width="1000" alt="Screenshot 2022-08-06 003035" src="https://user-images.githubusercontent.com/108232437/184506994-6d39d541-0d0c-46db-b531-f8030ec5c307.png">
