# Agri-Learning-Diagnosing-Plant-Diseases-using-Convolutional-Neural-Networks

Agriculture plays an imminent role not just for farmers, but for the entire world. One of the major problems farmers face is disease attacks which lead to plant loss and reduction in plant growth. 

In my methodology, In this paper, I have used the VGG-16 model (both pre-trained and one trained from scratch)  on a large PlantVillage Dataset to achieve higher accuracy. I have also trained our dataset on a CNN model to compare it to VGG-16.

The PlantVillage dataset consists of 54303 healthy and unhealthy leaf images that are further divided into 38 categories by the species name and disease.

## Results
1. The simple CNN model had the best validation accuracy score. The accuracy for trained images was 99.38 percent, while for validation images, it was around 89.5 percent.
2. The VGG-16 model that was built from scratch gave the lowest accuracy. It was first trained on the Adam optimizer for 100 epochs for which the training accuracy remained fixated between 14 to 17 percent
3. The pre-trained VGG-16 model successfully returned an accuracy of 99.91 percent on training images and 88.11 percent on the validation images when trained for 50 epochs

In addition, I also implemented Grad-CAM to determine exactly which areas of the leaf were used by the model in its prediction.

You can find the detailed research paper here: https://mehtaplustutoring.com/wp-content/uploads/2022/07/Agri-Learning.pdf
