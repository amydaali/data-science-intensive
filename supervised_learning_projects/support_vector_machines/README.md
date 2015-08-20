The use of the SVM algorithm was divided into sections with the goal towards maximizing the algorithm's accuracy.

**Conditions: full data + linear kernel**

Accuracy: .98

Training Time: 528 seconds

Testing Time: 52 seconds

**Conditions: 1/100 of data + linear kernel** 

Accuracy: .88

Training Time: .6 seconds

Testing Time: 3.9 seconds

**Conditions: 1/100 of data + rbf kernel**

Accuracy: .62

Training Time: .33 seconds

Testing Time: 2.87 seconds

**Conditions: 1/100 of data + rbf kernel + best C in [10,100,1000,10000] which was C = 10000**

Accuracy: .89

Training Time: .31 seconds

Testing Time: 2.36 seconds

**Conditions: full data + rbf kernel + C = 10000**

Accuracy: .99

Training Time: 395.49 seconds

Testing Time: 33.3 seconds

**Other Prompts:**

10th email prediction: 1 (Chris)

26th email prediction: 0 (Sarah)

50th email prediction: 1 (Chris)

Number of email predicted to belong to Chris: 877
