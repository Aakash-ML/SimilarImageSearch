# SimilarImageSearch
This repo contains the ml experiment that was used to find all the similar images in the database.

[Please Read PDF document in the repo](https://github.com/Aakash-ML/SimilarImageSearch/blob/master/Avatari_Doc.pdf)

#code details:- 
## Task 1
### To find similar images.

All the .ipynb are named as:- 

 * Avantari_TASK1_v1: Best performance, Used pretrained MobileNet, Imagesize 224x224x3
  
 * Avatari_TASK1_v2: Use of simple autoencoder, not the best
  
 * Avatari_TASK1_v2_3: Use of a bigger autoencoder without dropout layer, reconstruction better  than previous version but performance for similarity check still not comparable to pre-trained model.

## Task 2
### Image clustering
  * Avantari_TASK2_V1: Used pretrained MobileNet to extract feature then DBSCAN to cluster images.
  
### Reference
 https://towardsdatascience.com/building-a-similar-images-finder-without-any-training-f69c0db900b5
