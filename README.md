# cs224w-notes
Notes taken in the lessons from course CS224W on graph learning
## 5.1 - Message passing and Node Classification
- Main question: given network with some nodes unlabeled, how do we assign labels to them?
- Solution: message passing.
- Intuition: Correlations exist in networks (similar nodes are connected, have the same color/class) &#8594; collective classification
- Three techniques:
  - Relational classification
  - Iterative classification
  - Belief propagation
Main types of dependencies that lead to correlation (specially in social networks):
- Homophily: tendency of individuals to associante and bond with similar othersv  
- Influence
