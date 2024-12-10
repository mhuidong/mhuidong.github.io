---
title: "FedRRA: Reputation-Aware Robust Federated Learning against Poisoning Attacks"
collection: publications
date: 2023-06-18
venue: 'Proc. of IEEE International Joint Conference on Neural Network (IJCNN), CCF-C'
paperurl: 'https://ieeexplore.ieee.org/document/10191556'
---
**Liping Yi**, Xiaorong Shi, Wenrui Wang, Gang Wang, Xiaoguang Liu

**Abstract:** As an emerging machine learning paradigm, federated learning (FL) allows multiple participants to train a shared global model collaboratively on decentralized data while protecting data privacy. But traditional FL is susceptible to adversarial poisoning attacks, the global model in an FL system poisoned by adversaries may fail to converge or present accuracy degradation. To defend against data poisoning and model poisoning attacks simultaneously, we propose a Federated learning framework with a Reputation-aware Robust Aggregation (FedRRA) rule. It involves a two-step adversary detection: 1) a DBSCAN algorithm excludes models with obviously biased parameters and 2) an accuracy evaluation process punishes models with low accuracy. The reputation calculated in the two-step detection determines that clients with low reputations are removed before the aggregation, which alleviates the negative influence of models corrupted by adversaries. Extensive experiments demonstrate that FedRRA is superior to the state-of-the-art robust FL baseline in defending against model poisoning and data poisoning attacks.
