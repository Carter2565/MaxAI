# Learning Resources
Here are some resources I've been exploring to understand Deep Learning and related topics.

- [Playlist on Deep Learning](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi): A collection of 4 videos that explain the details of Deep Learning.

- [Matrix Multiplication Eigenvalue](https://www.youtube.com/watch?v=FX4C-JpTFgY): A video that explains matrix multiplication and its relationship to eigenvalues, shedding light on these essential mathematical concepts.

- [Understanding Eigenvalues](https://www.youtube.com/watch?v=DzqE7tj7eIM): A video that provides insights into understanding eigenvalues, a fundamental concept in linear algebra.

- [The Essence of Linear Algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&pp=iAQB): A comprehensive resource that delves into the essence of linear algebra. I watched Ep.1-9 and Ep.14, which can provide a deep understanding of this fundamental mathematical field.

- [3Blue1Brown's YouTube Channel](https://www.youtube.com/@3blue1brown/courses): A source of educational videos, great for understanding the basic math behind AI, including topics related to mathematics and AI.


# Basic Understanding
### Let's break down some fundamental concepts related to AI and neural networks.

># My Explanation:
> ## Ai uses metrics for its data:
>> Using the matrices (Input/Output) the training packages ([TensorFlow](https://www.tensorflow.org)) Or ([PyTorch](https://pytorch.org)) the computer (while training) adjusts the weights and biases of each neuron to edge closer to the end result.
>> ## Weights and Biases:
>> The float values that shift the output of each layer
># ChatGPT Explanation:
>> ## How AI Models Learn:
>> Artificial intelligence (AI) models, particularly neural networks, utilize matrices (often referred to as tensors) to represent input and output data. These models, typically implemented using frameworks like ([TensorFlow](https://www.tensorflow.org)) or ([PyTorch](https://pytorch.org)), are trained using datasets containing input data and their corresponding target outputs. During training, the computer adjusts the weights and biases of each neuron in the network to make predictions that closely match the target outputs.
>> ## Weights and Biases:
>> Weights are floating-point values that determine the strength of connections between neurons in different layers of a neural network. Biases are additional parameters that shift the output of each neuron. These weights and biases are essential for the model to make accurate predictions.


# The idea behind text based models:
># My Explanation:
>> ## Input:
>> The input for a text based model is quite simple, it is just vectored words
>> ## Output:
>>  For text based models we need to have an expected output. For example, a vectored answer to a vectored question.
>> ## The Process:
>>  When training a text based models each layer effects the output differently, having the right layers for your data set(s) is important. Using the frameworks we use a mix of the loss functions and layers in our model to shift our weights and biases finding the relations between the question and answers. Using the trained model with the correct weights and biases, the model is able to take a question as the input and return an answer with a relevancy and accuracy to the question based on the training data.
># ChatGPT Explanation:
>
>> ## Input:
>> The input for text-based models typically consists of vectorized words or sequences of words. These words are often encoded into numerical representations, such as word embeddings, to be processed by the model.
>> ## Output:
>> For text-based models, the goal is to generate meaningful text-based outputs. The output may be in the form of sentences, paragraphs, or other text structures. The output can vary based on the specific task, but it should be relevant and accurate.
>> ## The Process:
>> When training text-based models, each layer of the neural network affects the output differently. Choosing the right architecture, layers, and loss functions for your specific dataset and task is crucial. During training, the model learns to adjust its weights and biases to capture the relationships between input and output data.
>> 1. **Data Preprocessing**: Text data is typically preprocessed by tokenizing it into words or subword units and then converting these tokens into numerical vectors. This step may also involve techniques like padding sequences to ensure uniform input sizes.
>> 2. **Model Architecture**: The choice of neural network architecture depends on the task. Recurrent Neural Networks (RNNs), Convolutional Neural Networks (CNNs), Transformer-based models, and others can be used for different text-based tasks.
>> 3. **Loss Functions**: Loss functions are used to measure the dissimilarity between the model's predicted output and the actual target output. Common loss functions for text-based tasks include categorical cross-entropy for classification and mean squared error for regression.
>> 4. **Training**: During training, the model adjusts its weights and biases through backpropagation and optimization algorithms (e.g., stochastic gradient descent) to minimize the chosen loss function. This process involves iteratively presenting training examples and updating the model parameters.
>> 5. **Evaluation**: Text-based models are evaluated based on metrics specific to the task, such as accuracy, F1 score, BLEU score (for language generation tasks), or other relevant measures. Evaluation is crucial to assess the model's performance.
>> 6. **Inference**: Once the model is trained and fine-tuned, it can take new text input (e.g., a question) and generate output (e.g., an answer) with relevance and accuracy based on the patterns learned during training.
>> 
>> In summary, the idea behind text-based models is to process text input, learn from the data through training, and generate meaningful text-based output that is relevant to the specific task. The model architecture, loss functions, and training process play key roles in achieving this goal.
>
<sup style="position: absolute; right: 10px; padding: 10px;">[@Carter2565](https://Carter2565.dev)</sup>

