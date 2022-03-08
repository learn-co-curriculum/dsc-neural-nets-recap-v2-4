# Neural Networks - Recap

## Key Takeaways

The key takeaways from this section include:

### Neural Networks

* Neural networks are powerful models that can be customized and tweaked using various amounts of nodes, layers, etc.
* The most basic neural networks are single-layer densely connected neural networks, which have very similar properties as logistic regression models
* Compared to more traditional statistics and ML techniques, neural networks perform particularly well when using unstructured data
* Apart from densely connected networks, other types of neural networks include convolutional neural networks, recurrent neural networks, and generative adversarial neural networks 
* When working with image data, it's important to understand how image data is stored when working with them in Python
* Logistic regression can be seen as a single-layer neural network with a sigmoid activation function
* Neural networks use loss and cost functions to minimize the "loss", which is a function that summarizes the difference between the actual outcome (eg. pictures contain Santa or not) and the model prediction (whether the model correctly identifies pictures with Santa)
* Backward and forward propagation are used to estimate the so-called "model weights"
* Adding more layers to neural networks can substantially increase model performance
* Several activations can be used in model nodes, you can explore with different types and evaluate how it affects performance

### Deep Neural Networks

* Deep neural network representations can lighten the burden and automate certain tasks of heavy data preprocessing
* Deep representations need exponentially fewer hidden units than shallow networks, to obtain the same performance
* Parameter initialization, forward propagation, cost function evaluation, and backward propagation are again the cornerstones of deep networks
* Tensors are the building blocks of neural networks and a good understanding of them and how to use them in Python is crucial
* Scalars can be seen as 0-D tensors. Vectors can be seen as 1-D tensors, and matrices as 2-D tensors
* The usage of tensors reaches beyond matrices: tensors can have N dimensions
* Tensors can be created and manipulated using NumPy
* Keras makes building neural networks in Python easy, and you learned how to do that in this section
* You can use Keras to do some NLP as well, e.g. for tokenization 
