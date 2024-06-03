# Building a simple neural network “from scratch”

This repository contains the implementation of a simple neural network "from scratch" as part of the Deep Learning assignment at Ben-Gurion University of the Negev, Faculty of Engineering Sciences, Department of Software and Information Systems Engineering. The assignment aims to provide students with a hands-on experience in building and understanding the forward and backward propagation processes. Submission is to be done in pairs, and plagiarism is strictly prohibited.

## Functionality Implemented:

1. **Forward Propagation:**
   - Initialization of parameters
   - Linear and activation functions (ReLU, Softmax)
   - Forward propagation for the entire network

2. **Backward Propagation:**
   - Gradient computation for linear and activation functions (ReLU, Softmax)
   - Backward propagation for the entire network
   - Parameter updates using gradient descent

3. **Training and Prediction:**
   - Training of an L-layer neural network
   - Prediction of accuracy on provided data

**MNIST Classification and Analysis:**

1. **Network Configuration:**
   - 4 layers with sizes: 20, 7, 5, 10
   - Learning rate: 0.009
   - No batch normalization initially
   - Flattened input shape: [m, 784]
   
2. **Training Procedure:**
   - Train until no significant improvement on the validation set for 100 steps
   - Report training iterations, epochs, and batch size
   
3. **Results Analysis:**
   - Final accuracy values for train, validation, and test sets
   - Cost values for every 100 training steps

**Additional Experiments:**

1. **Batch Normalization:**
   - Repeat training with batch normalization turned on
   - Compare performance, running time, and training steps
   
2. **L2 Norm Functionality:**
   - Modify code to support L2 norm
   - Provide explanation and compare weight values with and without L2 norm
