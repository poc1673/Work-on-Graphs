# Machine Learning for Graphs

The purpose of this project is to work as my primer on machine learning in networks, with an emphasis on the application of these models for analyzing instances of money laundering or fraud in networks of transactions.

The focus of this project will be on academic literature and numerical experiments that have been implemented in literature in the past few years. Papers that are deemed as necessary precursors will also be reviewed.

Implementation will be in Python Tensorflow.

## Scope:

The scope will be a survey of each of the major methodologies used in machine learning for networks. At the time of this assessment (2020-12-19) this will be:

* Graph convolutional neural networks.
* Manifold propogation
* DeepWalk and skip-gram graph embeddings
* More simplistic methodologies such as the logistic regression framework used in earlier papers.

After reviewing and replicating the above results, a novel approach should be developed using a data-set. It should also be applied to data-sets related to fraud/money laundering networks. This novel implementation should begin with a motivation and derivation of the method, its performance, and a full explanation of how it works.

## Final Result:

1. Familiarity with major forms of machine learning for networks.
2. Original implementation of graph learning algorithm implemented.
3. Presentation of novel implementation compared to previous implementations using visualization and explanation.

## Timeline:

| Week # | Begin Date | Topic | Items Due |   
|------------|----------------------|-------|-----------|
| 1|  2021-01-10         |         | Graph theory/Tensorflow review      |           |   
| 2|  2021-01-18         |          | Convolutional neural networks and graph theory      |           |   
| 3|  2021-01-26          |          |    Manifold propogation   |           |   
| 4|  2021-02-02          |          |  Skip-gram graph embeddings (DeepWalk)     |           |   
| 5|  2021-02-10          |          |   FAST CGN Replication    |           |   
|6|  2021-02-18          |          | Create novel model.       |           |   
|7 | 2021-02-26          |          | Generate writeup on results.       |           |

### Week 1:
* Review theory for neural networks:
 + Basic principles of neural networks.
 + Structure of networks (RNN, et cetera).
 + Review of graph convolutional neural networks.

* Review of graph theory:
 + Convolutions and applications to graph theory.

* Tensorflow refresher with exercises:
 + Review graph structure, programming framework for TensorFlow.
 + Review backpropogation.
 + Tensorflow ML exercise #1: Solve unconstrained optimization problem.
 + Tensorflow ML exercise #2: Solve constrained optimization problem.
 + Tensorflow ML exercise #3: Fit linear regression from scratch, fit "two-stage" linear regression.
 + Employ simple machine learning on the graph structure to try to group data.


* Assigned Reading:
 + Read Link Based Learning - Lu Getoor - 2003
 + Read paper introducing Node2Vec
 + Review graph database methods.

### Week 2:
1. Read Semi-Supervised Classification on Graph Convolutional Networks - Kipf Welling - 2017.
2. Replicate their results using Tensorflow 2.0 (original implementation used earlier version).
3. (If possible) Implement custom functions for GCNN using Tensorflow.

### Week 3:



### Week 4:

1. Read DeepWalk Online Learning of Social Representations - Perozzi et al - 2014.
2. Attempt to replicate the results from DeepWalk using Tensorflow.
3. (If possible) Implement DeepWalk Online Learning of Social Representations - Perozzi et al - 2014


### Week 5:

* Read FASTCGN implementation paper.
* Implement changes from FASTCGN onto original GCNN functions to create fast versions.
* Attempt to replicate results from both papers.

### Week 6:

To reassess steps.


### Week 7:







Ending: 2021-02-28

## Resources

### Graph Theory

### Deep Learning
1. [Tensorflow 2.0 Website](https://www.tensorflow.org/guide/effective_tf2)
2. [Tensorflow cheat sheet](http://www.aicheatsheets.com/static/pdfs/tensorflow_v_2.0.pdf)
3. [Deep Learning with Python](https://www.amazon.com/Deep-Learning-Python-Francois-Chollet/dp/1617294438/ref=sr_1_1?dchild=1&keywords=francois+chollet&qid=1608392039&sr=8-1)
4. [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646/ref=sr_1_3?dchild=1&keywords=francois+chollet&qid=1608392039&sr=8-3)

## Data-sets
1. [Karate club data-set](http://networkrepository.com/soc-karate.php)
2. [Elliptic data-set](https://www.kaggle.com/ellipticco/elliptic-data-set)
