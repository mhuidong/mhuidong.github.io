---
title: "FFedCL: Fair Federated Learning with Contrastive Learning"
collection: publications
date: 2023-06-04
venue: 'Proc. of IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), CCF-B'
paperurl: 'https://ieeexplore.ieee.org/document/10095453'
---
Xiaorong Shi, **Liping Yi**, Xiaoguang Liu, Gang Wang

**Abstract:** Federated Learning (FL) is a new paradigm of distributed machine learning, which can effectively solve the problem of data islands with privacy protection. Typical aggregation in FedAvg causes the global model bias to local models of clients with more local data. When clients’ data is Non-IID, the global model can not fully learn the data distribution of clients with less data, which incurs unfairness to these clients and then uninspired them to participate in FL. To this end, we propose a real-time fairness adjustment algorithm for the global model based on model-level contrastive learning, called FFedCL. We calculate our special-designed contrastive learning loss and use Stochastic Gradient Descent (SGD) to adjust the global model. It aims to improve the similarity of the global model to the model of clients with less data, thereby improving the fairness of FL. We evaluate FFedCL on three Non-IID datasets. The experimental results present that FFedCL improves up to 7% accuracy while maintaining almost the lowest variance compared with the state-of-the-art baseline, demonstrating its effectiveness on FL’s fairness enhancement.

