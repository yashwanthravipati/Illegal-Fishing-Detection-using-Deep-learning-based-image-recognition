# REACH_AVCS

This home for our vessel classification system to detect illegal fishing activity in the marine protected areas.

The computational module consists of a deep learning model to identify vessel type by extracting specific features from regions of interest within collected images. The identified class of ship in combination with the location where the images were taken is used to identify Illegal Unreported and Unregulated (IUU) fishing activity in real-time. The classification model is trained using transfer learning from the VGG16, a pretrained image recognition convolutional neural network (CNN), by using publicly available and annotated vessel image datasets.


The developed model has high training & validation accuracy. 

The python libarary: DEEPSEAS-CODE_VF


Datasets used: Marvel Datasets (https://github.com/jeffreylancaster/marvel)

