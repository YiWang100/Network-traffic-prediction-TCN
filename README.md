# Network-traffic-prediction-TCN

# Network Traffic Prediction Using Transformer and Temporal Convolutional Network (TCN)

## Abstract

This repository contains a hybrid model for network traffic prediction that integrates Transformer and Temporal Convolutional Network (TCN) technologies. Our approach addresses the limitations of existing methods in capturing both long-term and short-term dependencies in network traffic data. The Transformer module captures global temporal relationships through a multi-head self-attention mechanism, while the TCN module models local and long-term dependencies using dilated convolution technology. Experimental results on the PeMSD4 and PeMSD8 datasets demonstrate that our method significantly outperforms current mainstream methods, especially in long-term prediction tasks.

## Research Content

The proposed model combines the strengths of Transformer and TCN to improve network traffic prediction performance. Key features include:
- **Transformer Module**: Utilizes multi-head self-attention to capture global temporal dependencies.
- **TCN Module**: Employs dilated convolutions to model local and long-term dependencies effectively.

Ablation studies confirm the contribution of each module to the model's performance, validating the effectiveness of our approach in various prediction scenarios.

## Data Download

The datasets used for training and evaluation are:
- **PeMSD4**: [Download link](https://pems.dot.ca.gov)
- **PeMSD8**: [Download link](https://pems.dot.ca.gov)

Please download and place the datasets in the `data` directory before running the model.

## How to Train the Model

To train the model using Python, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YiWang100/Network-traffic-prediction-TCN.git
   cd Network-traffic-prediction-TCN
