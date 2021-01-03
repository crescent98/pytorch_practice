# Transfer Learning
## based on https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

This is a (99.9%) based on the codes written upper
Appreciated to Pytorch, who always make me a better man

For Transfer Learning study: https://cs231n.github.io/transfer-learning/
Transfer Learning 정리: https://www.notion.so/Transfer-Learning-Example-4648dff086b64ed8a24b92a49bb947e8

This example is about two methods of transfer learning

1. Initialization: just the initialization of the weights and train the entire network

2. Fixed Feature Extractor: freeze the model except for the last fully connected layer, and train only the left one