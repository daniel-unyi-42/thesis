# My thesis: Graph Convolutional Neural Networks and Applications

Deep learning has achieved great progress in speech processing, language processing and
computer vision. In other applications, however, we often have to work with signals defined
on graphs rather than grids. Recently there has been a lot of interest in trying to apply
deep learning to graph-based data, as models of this kind can capture the interactions
between components in real-world networks.

In current thesis, I address the task of node classification and link prediction on large
graphs. I use a variational autoencoder with different graph convolutional layers, including
a novel layer based on the Lanczos algorithm. The capability of the proposed architecture
is confirmed in various numerical experiments.

I also investigate two possible applications related to bioinformatics. In one task, I perform
gene ontology classification based on the human protein-protein interaction network. I
show that the autoencoder successfully reconstructs the data, and the latent variables are
powerful predictors of gene ontologies. In the other task, I attempt to predict multiple
types of molecular interactions. I hypothesise that newly constructed links are newly
discovered connections, and I look for literature evidence to reinforce my hypothesis.

Evaluation confirms that by applying graph convolutions, we can accomplish the most
important graph-related modeling tasks, and the proposed architecture is able to provide
state-of-the-art results.

![alt text](https://github.com/daniel-unyi-42/thesis/blob/main/pubmed.png)
