# Deep-Learning

Projects for Deep Learning Class at University of Arkansas Fall 2022

**project1.ipynb** builds an MLP to perform classification task with the following data description:

*Training data: Training data is a set of tuples D<sub>train</sub> = {(x<sub>i</sub>, y<sub>i</sub>)|i ∈ N ∩ [1, 100 000]} with the size of |Dtrain| = 100 000. Every sample xi = (a<sub>i</sub>, b<sub>i</sub>) is a point in 2-dimensional space, which is drawn from a uniform distribution with a range of a<sub>i</sub>, b<sub>i</sub> ∈ [−5, 5]. Every x<sub>i</sub> corresponds to a binary label y<sub>i</sub> ∈ {0, 1}. y<sub>i</sub> = 1 if and only if x<sub>i</sub> is inside a circle centered by (0, 0) with a radius of 2.5, otherwise, y<sub>i</sub> = 0 if x<sub>i</sub> is outside that circle. 
* Validation data: Validation data D<sub>val</sub> follows the exact criterion of D<sub>train</sub>, but its size is |D<sub>val</sub>| = 20 000.
* Testing data (X, Y): Testing data D<sub>test</sub> also follows the exact criterion of D<sub>train</sub>, but its size is |D<sub>test</sub>| =
20 000.
