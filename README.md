# Semantic_Segmentation_Using_U-Net

In this project, we are implementing semantic segmentation of an aerial view dataset captured by a drone using U-Net model whose initial weights are pre-trained on the resnet models.

Particularly, we are taking two approaches here - 
1. Resizing the images and then using Resnet50 for providing initial weights for U-Net.
2. Creating patches first, then resizing the images and then using Resnet34 for providing initial weights for U-Net.

The dataset I have used for this purpose can be found at https://www.tugraz.at/index.php?id=22387. In case this link causes issues, the dataset can also be found at https://www.kaggle.com/datasets/bulentsiyah/semantic-drone-dataset. The high resolution aerial view images and masks in this dataset were implemenmted in this project.
