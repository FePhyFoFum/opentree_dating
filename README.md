# opentree_dating
Simple techniques for adding dates to opentree

## General concept
Because the open tree of life does not have branch lengths, the datasets that contribute to the open tree of life have branch lengths of different scales and sources, and the overlap with molecular data can be quite poor in some areas, this aims to add branch lengths to open tree by fixing nodes to ages from relatively large dated phylogenies (e.g., Hedges et al. 2014) and then splitting the difference for nodes that are not calibrated. This is done in a preorder fashion with the removal of conflicting ages as best as possible. The calibrations are present here in the repository and any edits are welcome. 

There are several ways in which this could be improved. In particular, including more comprehensive phylogenies. This will be updated as new estimates are completed and a webservice will soon be available. 

## Procedure
We use `scaletree` from the golang repository [https://github.com/FePhyFoFum/gophy](gophy).