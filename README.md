# Mapping-the-Networks-of-Voltaire-s-Philosophical-Dictionary
## Findings

The first step in this project was to modify Voltaire’s Philosophical Dictionary and divide it into 99 sub parts based on the lexical terms it contained. The division into sub parts was accomplished by using special character to separate one section from the other. From that we derived a Python dictionary constituting of lexical terms as the keys and their corresponding sub texts as the values. The next step was to look for references to other lexical term in each of the sub texts. 
If a reference to any other lexical term was found in the sub text, we formed a directed edge with the title/term of the sub text pointing to the referenced lexical term. In this way we formed the graph of lexical terms and references in Voltaire’s Philosophical Dictionary. From this graph, we then derived the largest strongly connected component.

Shown below is the directed graph of lexical items and references in Voltaire’s Philosophical Dictionary.

![](Images/largest_strongly_connected.png)
