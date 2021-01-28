# DSL2020-PPIs

Protein-protein interactions (PPIs) are essential to almost every process in a cell. Exploring PPIs is crucial for understanding cell physiology in normal and disease states. The knowledge of PPIs can be used for drug development and to assign roles (i.e., protein functions) to uncharacterized proteins. In this project, we investigate the utility of Graph Convolutional Networks (GCNs) [1] for the problem of predicting protein-protein interactions (PPIs). The totality of PPIs is presented in the form of an undirected network, we thus formulate the problem as a link prediction task by GCN.

As a part of our Data Science Lab Project, we successfully implemented GCN (Graph Convolution Network) for Link Prediction in Pytorch for the Yeast dataset[2]. Our model achieved around 91% average precision score. This project is completed by a team of following 4 members each responsible for a designated phase.

Phase 1: Problem Definition - Rihab Ziani
Phase 2: Data Preprocessing - Abderrazzak El Khayari
Phase 3: Implementation - Deepak Rastogi
Phase 4: Empirical Evaluations and Discussion - Vishvapalsinhji Ramsinh Parmar


[1] T. N. Kipf and M. Welling, “Semi-supervised classification with graph convolutional networks,” arXiv preprint arXiv:1609.02907, 2016.
[2] http://snap.stanford.edu/deepnetbio-ismb/ipynb/yeast.edgelist
