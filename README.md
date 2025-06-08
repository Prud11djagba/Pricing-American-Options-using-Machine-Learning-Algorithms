# Pricing-American-Options-using-Machine-Learning-Algorithms
This project  investigates the application of machine learning algorithms, particularly in the context of
pricing American options using Monte Carlo simulations. Traditional models, such as the Black-Scholes-
Merton framework, often fail to adequately address the complexities of American options, which include the
ability for early exercise and non-linear payoff structures. By leveraging Monte Carlo methods in conjunction
Least Square Method machine learning was used. This research aims to improve the accuracy and efficiency of
option pricing. The study evaluates several machine learning models, including neural networks and decision
trees, highlighting their potential to outperform traditional approaches. The results from applying machine
learning algorithm in LSM indicate that integrating machine learning with Monte Carlo simulations can
enhance pricing accuracy and provide more robust predictions, offering significant insights into quantitative
finance by merging classical financial theories with modern computational techniques. The dataset was split
into features and the target variable representing bid prices, with an 80-20 train-validation split. LSTM and
GRU models were constructed using TensorFlow’s Keras API, each with four hidden layers of 200 neurons
and an output layer for bid price prediction, optimized with the Adam optimizer and MSE loss function.
The GRU model outperformed the LSTM model across all evaluated metrics, demonstrating lower mean
absolute error, mean squared error, and root mean squared error, along with greater stability and efficiency
in training.
This project is jointly done with Callixte Ndizihiwe.


The data source used in this experimental investigation is a collection of historical data on all symbols in the
U.S equities markets from January to June 2013 (https://optiondata.org).
