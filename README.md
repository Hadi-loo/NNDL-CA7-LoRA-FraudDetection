# Neural Network and Deep Learning Course - LoRA and Fraud Detection in Credit Card Transactions

## Project Description

This project is a part of the Neural Networks and Deep Learning Course. The project is about the low rank adaptation of large language models (LoRA) and fraud detection in credit card transactions. The project is divided into two parts.

### LoRA

The first part is about the implementation of the low rank adaptation of large language models (LoRA). The LoRA model is a variant of the Transformer model that is used for fine-tuning large language models on small datasets. The model is trained to adapt the pre-trained language model to the target task by learning a low-rank transformation of the pre-trained model's parameters. We are using RoBERTa as the pre-trained language model and fine-tuning it on the [Quora Question Pairs (QQP)](https://quoradata.quora.com/First-Quora-Dataset-Release-Question-Pairs) dataset. 

### Fraud Detection in Credit Card Transactions

The second part is about the implementation of fraud detection in credit card transactions. We are going to use the [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset. The dataset contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, the positive class (frauds) account for only 0.172% of all transactions. The dataset contains only numerical input variables which are the result of a PCA transformation. We are going to use the discussed model in the provided paper to detect fraud in credit card transactions. To solve the problem of imbalanced data, we are going to use the Adaptive Synthetic Sampling (ADASYN) algorithm.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
