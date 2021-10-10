# Viewing-Decision-Trees-of-a-Random-Forest

A Random forest is a supervised algorithm used in machine learning which belongs to bagging in ensemble technique.
It is a group of Decisio trees, where each tree using a binary tree graph (each node has two children) to assign for each data sample a target value. 
The target values are presented in the tree leaves. To reach to the leaf, decision is made in on the sample in each node level, starting from root node,to which descendant node it should go. 
A decision is made based on the selected sample’s feature. 
Decision Tree learning is a process of finding the optimal rules in each internal tree node according to the selected metric.

Decision trees are much easier to interpret and understand. Since a random forest combines multiple decision trees, it becomes more difficult to interpret. 
Here's the good news – it's not impossible to interpret a random forest.

## Below are 4 ways to visualize Decision Tree from a Random Forest in Python

- print text representation of the tree with sklearn.tree.export_text method
- plot with sklearn.tree.plot_tree method (pip install matplotlib)
- plot with sklearn.tree.export_graphviz method (pip install graphviz)
- plot with dtreeviz package (pip install dtreeviz)
