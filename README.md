# Arithmetic-operations-with-RNNs
This assignment is part of the course *Introduction to Deep Learning*.

For this assignment, we focused on training decoder-encoder RNN networks to learn how to perform simple arithmetic operations, e.g. addition, subtraction and multiplication. The goal was to develop various RNN models to compute these operations in both text and image formats. In particular, we have built three models: 
- a text-to-text model, which after having received as input a text query containing two integers and an operand between them (+, - or x), it outputs a sequence of integers that match the actual arithmetic result of the given operation; 
- an image-to-text model doing the same operations as the previous model, but on a given sequence of images containing individual digits and an operand; 
- a text-to-image model which receives a text query and outputs a sequence of images corresponding to the result of the operation (only used for addition/subtraction data in this case). 