Neural Network Log Files for Debugging

We are providing several neural network log files to assist you in debugging your own neural network implementation. These logs display the internal value changes within the network during operation.

Neural Network Structure
The network consists of multiple user-defined layers. For example, the notation [4, 32, 16, 8, 3] describes a four-layer network with the following configuration:

 Input layer: 4 cells
 Second layer (hidden layer): 32 cells
 Third layer (hidden layer): 16 cells
 Fourth layer (hidden layer): 8 cells
 Output layer: 3 cells

Layer Composition
Each layer (excluding the input layer) contains the following components:

 Biases: One per cell
 Loss (Error): One per cell
 Weights: A matrix of shape [m, n], where:

 m = Number of cells in the previous layer
 n = Number of cells in the current layer
 
For debug purpose, we have provided initialized Biases, Weights.

Testing the Neural Network
To validate your neural network, use the provided test dataset, which consists of:

 Input values: First few columns
 Target (expected output) value: Last few columns
 
For optimal performance, we recommend using vector and matrix operations to handle these computations efficiently.