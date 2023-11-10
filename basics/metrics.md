---
layout: page
permalink: basics/metrics/
title: Metrics
---
The metrics used for evaluating machine learning systems are based on the task and the domain. 

# Classification
For a set of examples $X = (x_1,...x_N)$, for each e$x_i$, predict a category $c_i$ from the set $C=(c_1,...,c_K)$. An example of classification is the object recognition, where given an image, you try to predict the object. If $K=2$, the task is called binary classification task, otherwise a multi-class classification task.

## Accuracy
$$
Acc = \frac{Correct Predictions}{N} 
$$
Ratio of how many predictions the ML system got right.
For binary classification, 
$$
$$

## Error Rate
$$ 
Error Rate = \frac{Incorrect Predictions}{N} = (1 - Acc)
$$
