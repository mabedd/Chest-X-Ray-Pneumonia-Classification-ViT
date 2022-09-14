# Chest-X-Ray-Pneumonia-Classification-ViT
Fine-Tuning Hugging Face pre-trained model with ViT

![](https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs12890-020-01286-5/MediaObjects/12890_2020_1286_Fig2_HTML.png)

The **Vision Transforme**, or ViT, is a model for image classification that employs a Transformer-like architecture over patches of the image. An image is split into fixed-size patches, each of them are then linearly embedded, position embeddings are added, and the resulting sequence of vectors is fed to a standard Transformer encoder. In order to perform classification, the standard approach of adding an extra learnable “classification token” to the sequence is used.

![](https://production-media.paperswithcode.com/methods/Screen_Shot_2021-01-26_at_9.43.31_PM_uI4jjMq.png)

## **Hugging Face Library**
Hugging Face is a community and data science platform that provides: Tools that enable users to build, train and deploy ML models based on open source code and technologies.

![](https://miro.medium.com/max/1190/1*tAh0R8C8e9EHg3pBuBGoPQ.png)
The following implementation was done with the help of Hugging Face `Transformers` library using Google `vit-base-patch16-224-in21k ` pre-trained model for Fine-tuning.

## Data
The used data is **Chest X-Ray Images (Pneumonia)** available on [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
![](https://i.imgur.com/jZqpV51.png)

## Results
As the model was fine-tuned using Hugging Face lib, it achieved the following results:
| Validation Accuracy | Validation Loss |
|---------------------|-----------------|
|      0.97           |     0.07        |
