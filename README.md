# Deep-Learning-Module

I started by loading the dataset, checking for missing values, and scaling the features using StandardScaler.

I used a histogram to check the distribution of the target variable and a correlation heatmap to understand the relationships between the features.

I then split the dataset into training and testing sets and trained a basic ANN model with two hidden layers using ReLU activation and the Adam optimizer.

After evaluating the first model, I tried another ANN with more layers, neurons, and dropout. I also changed the learning rate, epochs, and batch size to see how the model performance changes.

Both models were evaluated using Mean Squared Error (MSE) and R2 Score. I also plotted the training loss to compare the models.

The dataset is available directly through sklearn, so no separate download is required.

The MSE and R2 scores of both models are displayed in the notebook, along with the training loss comparison graph. These results are used to check whether the changes made to the second model improved its performance.
