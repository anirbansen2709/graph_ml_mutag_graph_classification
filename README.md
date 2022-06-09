# graph_ml_mutag_graph_classification

Overview of Graph Classification with GNN - Graph classification requires a model to predict certain graph-level properties of a single graph given its node and edge features. Molecular property prediction is one particular application.

In genetics, a mutagen is a physical or chemical agent that changes the genetic material, usually DNA, of an organism and thus increases the frequency of mutations above the natural background level. 

**MUTAG** is a commonly used dataset for evaluating **graph classification algorithms**. Each graph in the dataset represents a chemical compound and graph labels represent their mutagenic effect on a specific gram negative bacterium". MUTAG is a dataset of 188 graphs - mutagenic aromatic and heteroaromatic nitro compounds. Graph nodes have 7 labels (i.e. all molecules contain atoms of 7 possible elements) and  each graph is labelled as belonging to 1 of 2 classes. We will run a graph classification task on this dataset using node information only.

Libraries used - Networkx, DGL, PyTorch



