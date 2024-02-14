# Node Centrality and Similarity Based Parameterised Model (NCSM) for Link Prediction

## Overview
The Node Centrality and Similarity Based Parameterised Model (NCSM) presents a groundbreaking approach to link prediction in graph machine learning. This model is designed to overcome the limitations faced by current methodologies, particularly in handling short-path networks and ego networks. By innovatively integrating node centrality and similarity measures with Graph Neural Network (GNN) technologies, NCSM sets a new standard for predicting potential new links between nodes in various networks.

## Introduction
Link prediction is crucial in numerous applications, from disease prediction and drug discovery to social network recommendations. Despite the critical role of existing models, their effectiveness is often hampered in specific network types. Our research introduces the NCSM, a model that leverages node centrality and similarity measures as edge features within a custom GNN layer. This integration allows for the effective utilization of topological information, making NCSM the first of its kind in parameterised GNN-based link prediction.

## Key Features
- **Innovative Integration**: Combines node centrality and similarity measures with GNN layers to enhance link prediction accuracy.
- **Customised GNN Layer**: A specially designed GNN layer that efficiently processes topological information of large networks.
- **Superior Performance**: Outperforms state-of-the-art models like Graph Convolutional Networks (GCNs) and Variational Graph Autoencoders (VGAEs) in benchmark tests.

## Model Evaluation
NCSM was rigorously evaluated on five benchmark graph datasets, encompassing thousands of nodes and edges. The model demonstrated exceptional performance, surpassing existing models across various metrics and datasets. This success underscores the model's effective use of topological information and its innovative approach to integrating node centrality and similarity measures.

## Applications
NCSM's versatile design makes it suitable for a wide range of applications, including but not limited to:
- Disease prediction
- Drug discovery
- Social network recommendations


## Requirements
- Python 3.x
- PyTorch
- PyTorch geometric
- NetworkX
- Scikit-learn

## Usage
Refer to the `examples` directory for detailed examples on how to apply NCSM to your link prediction tasks. Basic usage involves initializing the model with your dataset and training parameters, then training the model on your graph data.

## Contributing
We welcome contributions to the NCSM project. If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Our thanks to the graph machine learning community for their inspiration and support in the development of this model. Special thanks to the contributors of the benchmark datasets used in evaluating NCSM.

