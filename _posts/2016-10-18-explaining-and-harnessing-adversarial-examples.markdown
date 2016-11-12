---
published: true
title: EXPLAINING AND HARNESSING ADVERSARIAL EXAMPLES
layout: post
---
The fact that adversarial negative examples exist for any DNN is intriguing.
Namely, two visually indistinguishable images by human may be classified as two different classes with high confidence by any DNN. And a image appearing to be random noise may be labelled as a class with high confidence.

In this paper, the authors tried to give an explanation of the haunting adversarials and proposed adversarial training. Here I quote:
"
Linear behavior in high-dimensional spaces is suf- ficient to cause adversarial examples. This view enables us to design a fast method of generating adversarial examples that makes adversarial training practical. We show that adversarial training can provide an additional regularization benefit beyond that provided by using dropout (Srivastava et al., 2014) alone. Generic regularization strategies such as dropout, pretraining, and model averaging do not confer a significant reduction in a model’s vulnerability to adversarial examples, but changing to nonlinear model families such as RBF networks can do so.
"

## Related

1. CVPR15: Deep neural networks are easily fooled: High confidence predictions for unrecognizable images
2. http://www.kdnuggets.com/2015/07/deep-learning-adversarial-examples-misconceptions.html
3. Hitting Depth: Investigating Robustness to Adversarial Examples in Deep Convolutional Neural Networks