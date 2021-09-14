# R-HeartDisease
Experiment with clustering algorithms to help doctors inform treatment for heart disease patients.

## **Introduction** </br>
There are many industries where understanding how things group together is beneficial. For
example, retailers want to understand the similarities among their customers to direct
advertisement campaigns, and botanists classify plants based on their shared similar
characteristics. One way to group objects is to use clustering algorithms. We will explore the
usefulness of unsupervised clustering algorithms to help doctors understand which
treatments might work with their patients. We are going to cluster anonymized data of
patients who have been diagnosed with heart disease. Patients with similar characteristics
might respond to the same treatments, and doctors could benefit from learning about the
treatment outcomes of patients like those they are treating.

## **Conclusion** </br>
Now that we've tried multiple clustering algorithms, it is necessary to determine if we think any of them will work for clustering our patients. For the k-means algorithm, similar clusters must be produced for each algorithm iteration to make sure that the algorithm clusters the signal, not the noise. It’s also important for the k-mean algorithm to seem stable when running multiple iterations. This means that we would see similar groups of patients showing up in the plots
from the different iterations of the algorithm. For the hierarchical clustering, we need a
method that puts a balanced number of patients in each group.</br >
So the best algorithm that shows promise for this data is Hierarchical clustering with complete linkage.
