# TFM-DL-interpretability-and-image-segmentation
Github repository containing the necessary code for the elaboration of the Master's Thesis at UPC. The goal was to analyse different databases of different semantic background, trying out different CNN architectures and applying different deep learning interpretability methods to check the performances. Additionally, some of the images were segmented in order to check if there are any links to the corresponding deep learning interpretability heatmap.

This project is dealing with 4 different datasets:
  - MNIST
  - LFW (Labeled faces in the wild)
  - NT (nuchal translucency images, fetal ultrasound images)
  - CRL (crown-rump length images, fetal ultrasound images)

Every dataset has its own notebook. NT and CRL have additional notebooks for data augmentation. CRL has an additional notebook for adding some modifications to the images. NT and CRL images are provided by Hospital Sant Joan de Déu in Barcelona.
MNIST has an additional notebook for adding some perturbations.
