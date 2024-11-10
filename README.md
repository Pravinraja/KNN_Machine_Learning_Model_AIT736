# KNN_Machine_Learning_Model_AIT736
A sample coded use case of K-NN or a decision tree classifier where we applied to solve a real-world problem.  We will be describing the application, related data, training protocol, results. In this sample for the KNN ML Algorithm, we will use the topic of Parkinson's Disease Detection

K-Nearest Neighbors (KNN) is a simple machine learning algorithm used for classification and regression. In KNN, a new data point is classified by looking at the 'k' closest data points (neighbors) and assigning it the most common class among those neighbors. For regression, it predicts the average of the 'k' nearest neighbors' values. It’s non-parametric, meaning it makes no assumptions about the data distribution, but it can be quite intensive for large datasets.

For predicting Parkinson's disease, the KNN algorithm would take various patient measurements, in our case voice frequency as input data points. It would then classify new patients based on the closest 'k' data points with known Parkinson’s diagnoses, predicting whether the patient is likely to have the disease based on the majority characterstics of these neighbors. This approach leverages patterns in symptoms for early detection.

