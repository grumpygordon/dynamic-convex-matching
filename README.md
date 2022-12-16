Refer: https://tildeweb.au.dk/au121/papers/mfcs07matching.pdf

Online maximum matching in convex bipartite graph.
Convex graph is represented as array $a$ on one side and set of segments $b$ on the other side, segment from $b$ is connected with respective segment of array $a$.
Operations are
* add new segment
* delete existing segment
* $a[i]$++ or $a[i]$--
* get maximum matching size

All update operations are done in $O(\log^2 n)$ worst case, get operation is done in $O(1)$, $n$ is the number of nodes in graph (size $a$ + size $b$).
