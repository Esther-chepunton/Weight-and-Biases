# Weight-and-Biases Assignment
Weights and biases are fundamental concepts in neural networks and other machine learning models. They are used to adjust the strength of the connections between neurons (in the case of neural networks) or features (in the case of other models) and play a crucial role in learning from data.

**Weights**
Weights represent the strength or importance of the connection between two nodes (neurons) in a neural network. They are used to scale the input data as it is passed through the network. In the context of a neural network, each input feature is multiplied by a weight, and the results are summed to produce a weighted sum.

**Biases**
Biases are additional parameters in a neural network that allow the model to make adjustments independently of the input data. They are added to the weighted sum before applying the activation function, allowing the model to better fit the training data by shifting the activation function.

**How They Work Together**
In a neural network, the process works as follows:

Input Layer: The input features are fed into the network.
Weighted Sum: Each input is multiplied by its corresponding weight, and the products are summed together along with the bias term.
Activation Function: The weighted sum plus bias is passed through an activation function (like ReLU, sigmoid, or tanh) to introduce non-linearity into the model.
Output Layer: This process repeats across multiple layers, and the final output layer produces the prediction.

**Use Cases**
Weights and biases are used in various machine learning algorithms, including:

Neural Networks: Deep learning models with multiple layers and complex architectures.
Linear Regression: To model the relationship between input features and target values.
Logistic Regression: To classify binary outcomes.

**Observation of the results of the weight and Biases**
          Feature        Weight
0         ranking  8.858471e-08
3        card_rem  1.173399e-13
8      jaccard_AR -3.223256e-16
9      jaccard_AA -3.573589e-16
7      jaccard_RA -3.656243e-16
6      jaccard_RR -3.913997e-16
2      mld.ps_res -1.502481e-14
11  jaccard_ARrem -1.660339e-14
10   jaccard_ARrd -2.338845e-14
1         mld_res -3.291667e-14
4      ratio_Rrem -3.121680e-12
5      ratio_Arem -3.301572e-12
Bias (Intercept): -0.00

OBSERVATIONS:
1.some features have postive weights, while others have negative weights.For the positive the preiction tends to increase while the negative suggest the opposite.
