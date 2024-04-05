# TNSDC-Generative-AI-for-Engineering

Dataset Link : https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

System Requirements
1. Hardware
CPU: A multi-core CPU is sufficient for running the training code. However, training LSTM a type of RNN can be computationally intensive, so a faster CPU may reduce training time.
Memory (RAM): At least 8GB of RAM is recommended for handling large datasets and training deep neural networks efficiently. Higher RAM capacity may be beneficial for larger batch sizes and complex model architectures.
Internet Connection: An internet connection is needed to download the Amazon fine food reviews dataset and access online resources/documentation during development.

2. Software
Python: The project is implemented using Python programming language.
TensorFlow/Keras: TensorFlow and its high-level API, Keras, are used for building and training the LSTM a type of RNN architecture.
Google Colab: These platforms can be used for interactive development, experimentation, and documentation.
NumPy: NumPy is used for numerical computations and array manipulation.
Matplotlib: Matplotlib is used for data visualization, including plotting loss curves and displaying generated images.
Pickle: The pickle module in Python provides functionality for serializing and deserializing Python objects into a binary format, allowing for easy storage and retrieval of complex data structures.It's commonly used for data persistence and inter-process communication.

LSTM Architectural Design:
LSTM (Long Short-Term Memory) networks are a type of recurrent neural network (RNN) 	architecture designed to handle the vanishing gradient problem and capture long-term 	dependencies 	in sequential data.
 Encoder: Construct an LSTM network to encode the input text into a fixed-length vector representation. Experiment with variations in LSTM layer sizes, the number of layers, and dropout rates to optimize performance.
Decoder: Implement another LSTM network as the decoder to generate the summary based on the encoded vector. Use techniques such as teacher forcing to train the decoder efficiently.
Attention Mechanism: Incorporate an attention mechanism to allow the model to focus on relevant parts of the input text during summarization.




