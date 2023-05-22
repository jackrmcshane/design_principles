# Day 1 Notes

* quizzes are based on the YouTube videos!!!

Regularization is the problem of ensuring your model does not overfit to the training data


Tuesdays & Friday -- days professor discusses modules

gradient based learning is sensitivity analysis: "how sensitive are our ouputs to changes in the input we pass"
energy and direction of gradient: magnitude & direction



TOPICS:
Generative Adversarial Networks (GANs)
Federated Learning Approach
Autoencoders for ~PCA


DARPA Spectrum challenge


## MESSAGES FROM SHREYA ABOUT RESOURCES FOR FEDERATED LEARNING
Hi Jack, sure. The paper that introduces federated learning is here: https://arxiv.org/abs/1602.05629. This is an active area of research till date. Most research problems focus on several aspects of federated learning such as different aggregation algorithms(FedSGD, FedNova, FedAvg and I'm sure there are more!), the security aspect when weights are being exchanged(sharing gradients only vs sharing weights or something similar). There are even different types of federated learning like horizontal or vertical federated learning(this includes another technique called split training). You can also use federated learning for training different models over different devices and still use them to train one global model.


I do have a paper on transfer learning using federated learning. You can find the paper and the code here: https://github.com/ghosh64/fedlearn
