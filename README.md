# SCAN_clustering_summary
Summary of  [*"SCAN: Learning to Classify Images without Labels"*](https://arxiv.org/abs/2005.12320)   paper.


## Paper Overview: 
Convolutional neural networks have made breakthroughs in processing image, video, speech, and text and have recently been substantially improving upon the state of the art in image classification. But CNN often achieves their strong performance through supervised learning, which requires a huge amount of labeled dataset. But when there are no labels to train a network how do we get the network to learn meaningful features from the images?

Combining representation learning with clustering is one of the most promising approaches for unsupervised learning. The method described in the paper called SCAN(Semantic Clustering by Adopting Nearest neighbors) decouples the feature representation part and the clustering part resulting in a state of the art accuracy.

The authors try to solve the problem with 3 steps: Self Supervised Learning: a self- supervised task from representation learning tries to extract semantically meaningful features. 

Clustering: Clustering the similar representation using Nearest-neighbor- based Clustering. 

Self Labelling: using already well-classified images and fixing mis- takes through self-labeling.


SCAN method is the first to perform well on a large-scale dataset for image classification and shows promising results on ImageNet. Furthermore, it outperforms several semi-supervised learning methods with unlabelled data.