# Fashion-v2
Applying a very simple neural network model using Pytorch to Fashion MNIST

I applied here a simple neural network to the FashionMNSIT dataset (from the torchvision toolkit).
It is applied to a flattened version of an image, and is composed of one linear layer from the input to a second layer of 10 neurons (with ReLU activation functions).
A LogSoftMax layer is then applied and the loss function is a Negative Log Likelihood loss.

I trained it for roughly 40 minutes using Google Colab GPU and Adam optimizer.

The result was an 89% success rate, which is quite impressing for a model as simple as this one!

The model is contained in the file "NN1_model" of this repository, in the Pytorch format.
The code I used to set it up and train it is in the Jupyter Notebook "NN1_model.ipynb".
