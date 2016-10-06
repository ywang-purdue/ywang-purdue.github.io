---
published: true
title: Return of Devil
layout: post
---
In this paper, the authors intend to compare deep features extracted from different CNN methods to the previously state-of-art shallow features, or the handcraft features, such as Bag-of-Words and the improved Fisher Vectors. The authors evaluate shallow and deep representations on a common ground of object recognition tasks.

## Some key take-aways:

1. As for the shallow feature implementation, it seems that using spatially extended local descriptors instead of spatially pyramid and appending color features (Local Color Statistics) to the SIFT features give better result. However, the improvement by using color features is small if data augmentation is applied.

2. L2 normalization is important for both FV and deep features before applying SVM method for classification.

3. Augmentation works for both shallow feature and deep feature. (Cropping and flipping)

4. Combining deep feature and IFV makes little difference as the authors tested.

5. Deep features outperforms shallow features in terms of computational time and feature dimension.

## Related papers:

1. “Fisher Vectors Meet Neural Networks: A Hybrid Classification Architecture” CVPR15

2. “A practical guide to CNNs and Fisher Vectors for image instance retrieval” arXiv

3. “Food Image Recognition with Deep Convolutional Features”