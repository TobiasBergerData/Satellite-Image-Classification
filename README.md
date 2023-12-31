# Satellite-Image-Classification

In this project I got to work with a fun dataset. The Sentinel-2 satellite images are openly and freely accessible provided in the Earth observation program Copernicus. A group of researchers put some of them together to create novel dataset consisting out of 10 classes with in total 27,000 labeled and geo-referenced images. I used a deep learning approach, utilizing the RESNET50 architecture, to find an algorithm to classify the land use and land cover of the 64x64 pixel pictures as accurate as possible. 

Introducing image augmentation and an early stopping mechanism I reached an accuracy of ~87 % with my algorithm that was trained, using all 27k images, though only running for 20 epochs, due to computing power and time constraints. A higher accuracy with more training epochs would be expected. Looking at the confusion matrix afterwards allows us, what classes are easy to predict and which aren't. Interestingly the mistakes look fairly human, as we could as well misread highways for rivers at this image resolution.

The data set can be found here: https://github.com/phelber/EuroSAT.
