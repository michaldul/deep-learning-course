### Deep Learning, Udacity ud730
Assignments solutions. Note: I use sanitized validation and test set (as in Problem 5 of the first assignment).
Scores:

1. **notmnist**
  * LogisticRegression and OneVsAllClassifier (sklearn): test 88.0%, valid 80.0%
2. **fullyconnected** 
  * Multinomial classifier trained with gradient descent on partial data (10000 samples), 801 steps: test 80.7%, valid 72.9%
  * Multinomial classifier with SGD, 5001 steps: test 85.6%, valid 77.7%
  * Neural network 784 x 1024[RELU] x 10, SGD, 5001 steps: test 88.4%, valid 80.8%
3. **regularization**
  * Multinomial classifier, SGD, L2 regularization, 5001 steps: test 88.4%, valid 80.3%
  * NN 784 x 1024[RELU] x 10, SGD, L2 regularization, 5001 steps: test 93.6%, valid 86.6%
