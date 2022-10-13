# Machine Learning

## What is Machine Learning?

Artificial intelligence, which is widely defined as a machine's ability to mimic intelligent human behaviour, includes the subfield of *machine learning*. Artificial intelligence (AI) systems are used to carry out complicated tasks in a manner akin to how people solve issues.

In classic terms, machine learning is **a type of artificial intelligence that enables self-learning from data and then applies that learning without the need for human intervention**.

The 4 types of learning in Machine Learning are:

1. Supervised Learning.
2. Unsupervised Learning.
3. Semi-Supervised Learning.
4. Reinforcement Learning.

### Supervised Learning

In Supervised Learning we estimate the outcome based on well-labeled training data that has been used to train them. The term "labelled data" refers to input data that has already been assigned the appropriate output. The training data provided to the machines work as the supervisor that teaches the machines to predict the output correctly.

Finding a *mapping function* to link the input variable (x) with the output variable is the goal of a supervised learning algorithm (y).

#### Steps involved in Supervised Learning:

* Identify the training dataset type.
* Collect the labelled training data.
* Create *training*, *test*, and *validation* datasets from the training dataset.
* Identify the training dataset's input features, which should have sufficient details to enable reliable output prediction.
* Choose the best method for the model, such as a decision tree, random forest a support vector machine.
* Apply the algorithm on the practice data. Validation sets, a subset of training datasets, are occasionally required as control parameters.
* Use the test set to determine the model's correctness. If the model correctly predicts the outcome, then it is accurate.

#### Types of *Supervised Learning* Algorithms:

1. **Regression:**

   * Regression Trees
   * Linear Regression
   * Polynomial Regression
   * Bayesian Linear Regression
   * Non-Linear Regression
2. **Classification**:

   * Decision Trees
   * Random Forest
   * Logistic Regression
   * Support vector Machine

#### Advantages of Supervised learning:

- With supervised learning, we can be certain of the object classes.
- We use the supervised learning model to address a variety of real-world issues, including spam filtering and fraud detection.

#### Disadvantages of Supervised learning;

- Models of supervised learning are inadequate for dealing with difficult tasks.
- If the test data and training dataset are not the same, supervised learning cannot predict the right result.
- Training required lots of computation times

### Unsupervised Learning

Models are not supervised using training datasets while utilizing the machine learning technique known as unsupervised learning. Instead, models themselves decipher the provided data to reveal hidden patterns and insights.

Finding the underlying structure of a dataset, classifying the data into groups based on similarities, and representing the dataset in a compressed format are the objectives of unsupervised learning.

#### Types of *Unsupervised Learning* Algorithms:

1. **Clustering**
   Using the clustering technique, items are grouped into clusters so that those who share the most similarities stay in one group and share little to none with those in another. The data objects are classified based on the existence or lack of commonalities discovered by cluster analysis.
2. **Association**
   An unsupervised learning technique called an association rule is used to uncover the connections among the variables in a sizable database. It establishes the group of items that co-occur in the collection. Association principle improves the efficacy of marketing strategy.

Some Popular unsupervised learning algorithms are:

1. K-means Clustering.
2. KNN (k-nearest neighbors).
3. Hierarchical Clustering.
4. Anomaly Detection.
5. Neural Networks.

#### Advantages of Unsupervised Learning:

- Compared to supervised learning, unsupervised learning is employed for problems that are more complex since it lacks labelled input data.
- Unsupervised learning is preferred because unlabeled data is simpler to obtain than labelled data.

#### Disadvantages of Unsupervised Learning:

- Due to the lack of a comparable output, unsupervised learning is inherently more challenging than supervised learning.
- Given that input data are not labelled and algorithms do not know the exact output in advance, the outcome of an unsupervised learning method may be less accurate.

### Semi-Supervised Learning

Between supervised and unsupervised machine learning, semi-supervised learning is a crucial subcategory.The training set for this algorithm consists of both labelled and unlabeled data. While there is a significant amount of unlabeled data, there is a relatively little amount of annotated data. An unsupervised learning technique is first used to cluster comparable data, and it also aids in labelling the unlabeled data into labelled data. It is for this reason that labelled data is more expensive to acquire than unlabeled data.

Usages of Semi-supervised learning:

- Speech Analysis.
- Protein sequence classification.
- Web content classification.

#### Working of Semi-Supervised learning algorithms:

- First, it uses less training data to train the model than supervised learning algorithms do. Up until the model produces accurate results, training is ongoing.
- The algorithms then employ the unlabeled dataset with fictitious labels, and the outcome may no longer be correct.
- Labels from labelled training data and data with fictitious labels are connected.
- Unlabeled training data and labelled training data share the same input data.
- Finally, train the model once more using the fresh combined input as you did in the first phase. It will lessen errors and increase the model's accuracy.

### Reinforcement Learning

By executing actions and observing the outcomes of those actions, an agent learns how to behave in a given environment via reinforcement learning, a feedback-based machine learning technique. The agent receives positive feedback for each successful action, and receives negative feedback or a penalty for each unsuccessful action.

Without any labelled input, the agent learns automatically in Reinforcement Learning.

***reinforcement learning is a type of machine learning method where an intelligent agent (computer program) interacts with the environment and learns to act within that.***

#### Types of Reinforcement learning:

- Positive reinforcement.

  Positive reinforcement learning entails doing something to make it more likely that the desired behaviour will recur. It has a favourable effect on the agent's conduct and makes that behaviour stronger.
- Negative reinforcement.

  The reverse of positive reinforcement, negative reinforcement learning enhances the likelihood that a particular behaviour will take place again by avoiding the undesirable circumstance.

#### Applications of Reinforcement learning:

* Robotics
* Game Playing
* Finance Sector (To evaluate trading strategies)
