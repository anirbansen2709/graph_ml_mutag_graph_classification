# graph_ml_mutag_graph_classification

MUTAG is a collection of nitroaromatic compounds and the goal is to predict their mutagenicity on Salmonella typhimurium. Input graphs are used to represent chemical compounds, where vertices stand for atoms and are labeled by the atom type (represented by one-hot encoding), while edges between vertices represent bonds between the corresponding atoms. It includes 188 samples of chemical compounds with 7 discrete node labels.

Libraries used - Networkx, DGL, PyTorch

Overview of Graph Classification with GNN - Graph classification requires a model to predict certain graph-level properties of a single graph given its node and edge features. Molecular property prediction is one particular application.

