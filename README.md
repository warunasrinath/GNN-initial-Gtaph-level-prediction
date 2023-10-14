# GNN-initial-Gtaph-level-prediction

![GNN introduction with first project](https://github.com/warunasrinath/GNN-initial-Gtaph-level-prediction/assets/56961480/307a2323-2935-4fc3-bdb9-7ec2a54954e8)

This process resembles the pooling layer in a Convolutional Neural Network. Let's compare the photo above with the one below. The distinction between the two is that the upper photo performs pooling on an image, while the lower photo performs pooling on a graph.

What does "pooling graph" mean, you ask? It means iteratively reducing the graph by removing nodes.

Now, observe this: in the initial stage, we start with five nodes before applying the first pooling operation. After completing the second pooling operation, we are left with only two nodes.
![GNN introduction with first project2](https://github.com/warunasrinath/GNN-initial-Gtaph-level-prediction/assets/56961480/adafb1cc-42de-4056-b2a4-6b785d35558e)

# Difference pooling techniques in GNN

1. Diffpooling technique 
![diffpool in gnn](https://github.com/warunasrinath/GNN-initial-Gtaph-level-prediction/assets/56961480/768131e8-782a-4074-b335-e13c87dac1ff)

2. Top-k Pooling technique
Take all the nodes and arrange the nodes as vector and based on the values of the vector, then select top-k nodes and create a new graph
![topk pooling1](https://github.com/warunasrinath/GNN-initial-Gtaph-level-prediction/assets/56961480/5106b099-6fbb-44bf-8293-d735d04b7637)

*. We can use a super node(which should be added additionally to the graph), All the information of other nodes is collected by the supernode. 
![supernode](https://github.com/warunasrinath/GNN-initial-Gtaph-level-prediction/assets/56961480/25b3ab76-9620-4f78-ab9a-677b87e526c3)




