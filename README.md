# AdvancedLearningAlgorithmsAndrewNg
Hi , the course is getting started from the neural network ,and how at each neuron it is just linear regression or logistic regression. But keep focus on the general writing of the output and input relation at each neurons.

Basic terminology :

![refer this for explaination](images/NN_neuron_InputOutput.png)
- subscirpt j refers to the specific neuron
- superscript l refers to specific layer  
- a vector  refers to activation (output or referred as prediction in ML models)
- w refers to weights (this vector size will be equal to number of neurons in previous layer , otherwise dot product with       previous output won't be possible , think about it)
- b refers to bias (scalar for specific neurons)
Just think about the size of a and w for each layer , it will give some good insights about the architecture of the NN.

Though course is starting from TensorFlow like how to build NN with the help of this and all but first we will build with NumPy and come back to this.


