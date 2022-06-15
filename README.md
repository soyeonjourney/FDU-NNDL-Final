<h1 align = "center">Oracle Character Recognition (2022 Spring)</h1>

Oracle character recognition is a challenging task due to the data limitation and imbalance, and the high degree of intra-class variance in the shapes of oracle characters. In this project, we try to solve k-shot learning tasks for three different settings of $k=1, 3, 5$. We first utilize a large-scale of unlabeled source data to train an Orc-Bert data augmenter, and use it to augment the original dataset. After that, we try two classifiers to recognize the oracle characters. One is the classical classifier like ResNet. The other is our proposed classifier, which is a combination of Content-Based Image Retrieval and Siamese Network. Both of these two models show good results in recognizing the oracle characters. For the classical classifier ResNet-18, the top-1 accuracy for all 200 classes are 40.88$\%$, 66.83$\%$ and 76.55$\%$ for $k=1, 3, 5$, respectively. For our proposed model, the results also indicate that this model may lead to higher accuracy for recognizing the oracle characters.

