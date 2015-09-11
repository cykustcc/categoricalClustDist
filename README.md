categoricalClustDist
===========

CategoricalClustDist is a python tool to compute the difference between two clustering results.
Clustering result is read from files in the format like `cluster_resultsA.txt` and `cluster_resultsB.txt`.	

More details please refer to Section 4.1 of "A New Mallows Distance Based
Metric for Comparing Clusterings", Ding Zhou, Jia Li, Hongyuan Zha.

Required packages
===========
- [cvxopt](http://cvxopt.org) 
- [numpy](http://www.numpy.org)
- [scipy](http://www.numpy.org)

How to run
===========
After proper configuration in categoricalClustDist.py.

`python categoricalClustDist.py`