# NEONATE
NEONATE: A Binary Search Strategy on Non-overlapping Pattern Matching with Gap Constraint

Pattern matching calculates support or occurrence numbers of a pattern in information retrieval and has derived kinds of constraints. Among the variety of constraint-matching conditions, plenty of research has illustrated the significant non-overlapping condition, which means that any two occurrences cannot use the identical character of the sequence in the same position of the pattern. Although a corresponding completeness proof has been given in state-of-the-art works, there is still room to improve the matching process. Inspired by the literature on strict matching under the non-overlapping condition, this study proposes a Nettree-based approach to matching given patterns called NEONATE. It adopts a bi-directional search strategy and pruning operation to realize the non-overlapping pattern matching under the gap and length constraints. NEONATE first locates the horizontal layer with the fewest available nodes in the Nettree. Then, it iteratively seeks the rightmost parent and rightmost child node until an occurrence is obtained in which the nodes in the Nettree path can strictly satisfy the pattern constraint. This study has not only demonstrated the completeness of NEONATE but also analyzed the complexity of the algorithm. The correctness and efficiency of NEONATE have been proved via extensive experiments on biological and musical sequential data.

Algorithms:

C++
