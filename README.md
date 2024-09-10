# ML-Assignment1_Sondre_Solbakken
This is the entire code i made to finish the tasks given in this assignment. I read and modified the csv file SpotifyFeatures.csv for use of supervised machine learning and logistic regression. I have used the dataset to check accuracy of the model i made in the code and to visualize the datapoints we are working. In my report i explained the key concepts and topics of logistic regression, supervised learning, cross entropy loss function and the stochastic gradient decent (SGD). I describe my data process and presented the results. I found the number of samples and features both from the original and reduced dataset. I plotted the datapoints from the reduced dataset and found that there a lot of overfitting to the top
left where the liveness and loudness are close to zero which means it can be difficult for the model to predict since the features are so merged. I implemented the logistic regression with use of SGD and calculated the accuracy of the training and testing set as well asplotting the training error as function of epochs. Lastly i made a confusion matrix for more precise insight into the accuracy of the model where i found the prediction of pop music to be more accurate than the classical music. Overall there was a high precentage of over 90% which would mean that the model was a good fit for the predicitons of genres.

The code with the csv file and the saved figures is in the master branch.