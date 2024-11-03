# Neural Networks

Neural networks are machine learning programs or models that make decisions similar to the human brain. They are a set of algorithms that use software and hardware to process information and can change their form based on the data they analyze.

Every neural network layer consists of nodes, through which the data is processed, analyzed, and an output is generated. 

## Layers of Neural Networks

1. **Input Layer**  
   This layer accepts the data that needs to be processed. There are many nodes that accept multiple inputs.

2. **Hidden Layer**  
   This layer carries out all kinds of processing that the input data undergoes to generate an acceptable output.  
   There can be any number of layers in this section, and the connections between each layer happen through channels.  
   Here, each neuron is assigned a numeric value called bias, and they undergo a threshold function known as the activation function to determine if the neuron should activate or not. Only activated neurons transmit data to the next layer.

3. **Output Layer**  
   After passing through all the layers in the hidden layer, the data reaches the output layer, where the neuron with the highest probability or value determines the output. 

### Forward and Backward Propagation
The movement of data in the forward direction is called **forward propagation**.  
If the output does not match the result or if there is a significant error margin, we feed the data back to the model, and the data moves from the output layer to the input layer. This process is known as **backward propagation**.

## Types of Neural Networks

1. **ANN – Artificial Neural Network**  
   This type of neural network passes data or neurons at each layer in the forward direction, hence they are known as Feed-Forward Neural Networks. They are one of the simplest variants, as they pass information in one direction through various input nodes until it reaches the output node.  
   **Applications:**  
   - Image and speech recognition  
   - Natural language processing  
   - Medical diagnosis  

2. **CNN – Convolutional Neural Network**  
   Convolutional Neural Networks (CNNs) are among the most popular models today. They are specialized deep learning architectures designed for processing structured grid data, such as images. They are particularly effective in visual tasks due to their ability to automatically learn spatial hierarchies of features. CNNs contain one or more convolutional layers that can be either entirely connected or pooled. These convolutional layers create feature maps that record a region of the image, ultimately broken into rectangles for nonlinear processing.  

3. **RNN – Recurrent Neural Network**  
   Recurrent Neural Networks (RNNs) are designed for processing sequential data, such as time series or natural language. They feature loops in their architecture, allowing information to persist across time steps, effectively capturing temporal dependencies and relationships in data sequences. RNNs train themselves from the outputs generated from the data they receive, aiming to reduce errors. However, this training process may take considerable time.  
