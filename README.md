AIM: Train a small feedforward neural network to classify non-linear data. 
ALGORITHM : Two-layer dense network with ReLU hidden units and sigmoid output, trained with Adam.
DETAILED EXPLANATION : 1. make_moons creates non-linear two-class data. 
2. Model: Dense(8, relu) hidden layer; Dense(1, sigmoid) output for binary classification. 
3. compile chooses optimizer & loss; fit trains the network via backpropagation. 
4. Evaluate on test set using prediction threshold 0.5. 

SAMPLE OUTPUT : NN test accuracy: 0.92 

RESULT: Neural networks model non-linear boundaries; students see improved accuracy over linear methods.

THEORY: With non-linear activations, networks approximate complex decision boundaries (universal approximation). 
