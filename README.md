# REACH_AVCS

This home for our vessel classification system to detect illegal fishing activity in the marine protected areas.

The computational module consists of a deep learning model to identify vessel type by extracting specific features from regions of interest within collected images. The identified class of ship in combination with the location where the images were taken is used to identify Illegal Unreported and Unregulated (IUU) fishing activity in real-time. The classification model is trained using transfer learning from the VGG16, a pretrained image recognition convolutional neural network (CNN), by using publicly available and annotated vessel image datasets.


The developed model has high training & validation accuracy. 

<img width="1311" alt="Screen Shot 2022-01-30 at 11 05 13 PM" src="https://user-images.githubusercontent.com/87992684/152078340-accfc764-be9c-4bde-9f04-d54b0374831a.png">

High Precision and Recall.


<img width="644" alt="Screen Shot 2022-02-01 at 7 21 08 PM" src="https://user-images.githubusercontent.com/87992684/152078462-78a19f4b-d0a2-426b-8ef5-7bfee0fe5452.png">


Peformed well on test dataset.

<img width="601" alt="Screen Shot 2022-02-01 at 7 21 57 PM" src="https://user-images.githubusercontent.com/87992684/152078528-48863c7e-7132-442f-b5e9-b2dc55108c61.png">


Datasets used: Marvel Datasets (https://github.com/jeffreylancaster/marvel)

