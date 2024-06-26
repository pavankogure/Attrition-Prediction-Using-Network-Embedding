# Attrition Prediction Using Network Embedding

In this project we aim to develop a model based on the network embedding techniques so that we can get enhanced attrition prediction. Many other studies used the traditional approaches using machine learning or deep learning methods, in which the attrition prediction is done based on individual features. But in our study, we aim to develop a model based on network embedding so that it utilizes or captures the relationships and interconnections between the employees and the other features. So, we can say that the traditional approaches will eliminate the interconnections between theemployees as they only rely on individual features. In order to overcome this drawback, we are using the network embedding technique, which is a graph-based data analysis, to capture the structural information of networks and represent it in a lowerdimensional vector representation by preserving structural and semantic information.

Here we are using the IBM HR dataset from Kaggle https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset. First we will build the network graph based on the features in the dataset and then use the network embedding techniques to generate the embeddings. For this project we have used three network embedding techniques which we used are the DeepWalk, Sparse Random Projection, and Graph Neural Network. We have tried to compare all three to find the best suitable network embedding technique for this research study. The three different network embedding techniques we used each have a different approach to reduce the network data into low-dimensional space.

DeepWalk is one of the node embedding techniques that is inspired by the Word2Vec model. It generates node embedding by random walks on a graph and learns representations to retain neighborhood. DeepWalk enables us to identify hidden features that affect attrition, such as relationships.

Graph Neural Networks is an effective approach for employee attrition predictions, it is suited for complex data that is represented as graphs. GNN’s enhance the abilities of conventional neural networks by allowing them to gather information from nodes and transmit it to other layers.

Sparse Random Projection is a dimensionality reduction technique that is used for large dimensional employee attributes. It is more memory efficient and computes large data with less computational power.

So we will compare all three techniques based on their performance, which was mainly evaluated using accuracy, precision, recall, auc roc score metrics.
