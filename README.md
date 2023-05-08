# Deploy-a-CNN-in-AWS-image-features-extraction-and-ACP

* This project consists in running a CNN (MobileNet-V2) in an AWS Elastic Map Reduce(EMR) Cluster in order to extract features of 100 images of fruits which are stored in AWS Simple Storage Solution (S3). <br>
* The idea is to validate the image processing chain on a small number of images so that it can be used when the number of images will increase dramatically (the scaling can be easily performed by adding more EMR clusters).<br>
* Once extracted, the features are stored in AWS S3 and a Principal Component Analysis (PCA) is performed.<br>


* Example of the AWS EMR cluster configuration :<br>
![cluster_EMR](https://user-images.githubusercontent.com/107719618/227430001-ec0aaa89-d528-42ad-9d03-6478756eb337.png)


<br>
* Illustration of the result of the PCA :<br>

![PCA](https://user-images.githubusercontent.com/107719618/227430025-f9b1be6a-e054-40f0-a093-0ff0efaf7692.png)
