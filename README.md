# neural-network-challenge-1

## The subject of this exercise is Student Loan Risk with Deep Learning
- Using tools such as:
- [Pandas](https://pandas.pydata.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://www.tensorflow.org/guide/keras)
- [Scikit-Learn](https://scikit-learn.org/stable/index.html)
- and a csv file provided by [edx](https://www.edx.org/boot-camps/coding)

## The Process
1. Review the data to check how balanced or inbalanced the available data is
2. Create features and target datasets
3. Split the datasets into training and testing datasets
4. Scale the features datasets ( StandardScaler was used in this excercise )
5. Create and define the Layers for the model
6. Add the layers to the model
7. Compile the model and fit it with the training dataset
8. Evaluate the results of the model
9. Save the trained/fit model to a Keras file
10. Reload the model as if it was a different training/testing operation
11. Predict results using the test dataset
12. Store the prediction values to a dataset
13. Run a Classification Report to evaluate the results

## Results
- The configuration used returned a 75% Accuracy.
- Different configurations of the number of layers and/or nodes per layers can be experimented with in order to improve the efficiency of the model with the current available data
