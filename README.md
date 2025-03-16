# Semantic_Segmentation_Using_U-Net

In this project, I am implementing semantic segmentation of an aerial view dataset captured by a drone using U-Net model whose initial weights are pre-trained on the resnet models.

Particularly, two approaches are taken here - 
1. Resizing the images and then using Resnet50 for providing initial weights for U-Net.
2. Creating patches first, then resizing the images and then using Resnet34 for providing initial weights for U-Net.

The dataset I have used for this purpose can be found at https://www.tugraz.at/index.php?id=22387. In case this link causes issues, the dataset can also be found at https://www.kaggle.com/datasets/bulentsiyah/semantic-drone-dataset. The high resolution aerial view images and masks in this dataset were implemenmted in this project.

Please take a look at the following to better understand the architectures mentioned above - 

1. Resnet - https://www.youtube.com/watch?v=woEs7UCaITo&ab_channel=DeepLearningwithYacine and https://www.youtube.com/watch?v=ulmx0ZVIqco&ab_channel=Vizuara
2. U-Net - https://www.youtube.com/watch?v=GAYJ81M58y8&ab_channel=DigitalSreeni


# Future scope
Based on the predicted mask, may try to find the relative area and classify the region as per requirements. Still looking into it, and may expand it for thermal images also. An interactive interface will be a great addition, nonetheless.


