# Deep-Learning

Projects for Deep Learning Class at University of Arkansas Fall 2022

**project1.ipynb** builds an MLP to perform classification task with the following data description:
*Training data: Training data is a set of tuples Dtrain = {(x<sub>i</sub>, y<sub>i</sub>)|i ∈ N ∩ [1, 100 000]} with the size of |Dtrain| = 100 000. Every sample xi = (ai, bi) is a point in 2-dimensional space, which is drawn from a uniform distribution with a range of ai, bi ∈ [−5, 5]. Every xi corresponds to a binary label yi ∈ {0, 1}.
y<sub>i</sub> = 1 if and only if x<sub>i</sub> is inside a circle centered by (0, 0) with a radius of 2.5, otherwise, y<sub>i</sub> = 0 if x<sub>i</sub>
is outside that circle. See the below figure for a demonstration of training data.
* Validation data: Validation data Dval follows the exact criterion of Dtrain, but its size is |Dval| = 20 000.
* Testing data (X, Y): Testing data Dtest also follows the exact criterion of Dtrain, but its size is |Dtest| =
20 000.
