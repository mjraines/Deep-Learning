# Deep-Learning

Report:

Overview:  The goal of this challenge is to create a binary classifier that predicts whether applicants will be successful if they are funded by Alphabet Soup.


Results:
The target variable is “IS_SUCCESSFUL” and the features are:  Application Type, Affiliation, Classification, Use Case, Organziation, Status, Income Amount, Ask Amount, & Special Considerations. The variables that are neither Targets or Features were EIN and Name

At the start of this model, I chose two hidden ReLU layers with 8 and 6 neurons with an output Sigmoid layer. I believed that ReLU are the most common activation functions, and I chose 8 and 6 neurons per our usual methods from class. The Sigmoid function is bound to 1 neuron by default for the output.


Summary:  The keras model was close to hitting the 75% target with 73% performance. Even with adding more layers the model did not appear to improve. Next time, using the RFC may help with outliers potentially. Definitely will be worth a shot to explore when I have more time on my hands soon! 
