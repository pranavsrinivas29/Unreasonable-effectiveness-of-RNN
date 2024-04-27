# Unreasonable-effectiveness-of-RNN
Inspired from the famous blog “The Unreasonable Effectiveness of RNN” by Andrej Karpathy. In embarking upon an exploration of this blog, it is imperative to first extend our sincerest appreciation to Andrej Karpathy for his illuminating work in the realm of artificial intelligence. Through his insightful blog post originally penned in 2015, Karpathy has not only provided a scholarly analysis but has also sparked a profound paradigm shift in our understanding of recurrent neural networks (RNNs).

Here I have explored three major scenarios where RNN acts as character language model. Firstly, we shall discuss about RNN will learn English words. The model is trained on dialogues from the Shakespeare’s plays. Next, RNN is fed with text file containing the several baby names and trying to generate new names of the desired length. Lastly, we are going to discuss how RNN can generate latex codes when set of latex codes are fed as the input. Due to vanishing gradient problem, we have chosen simple LSTM model, a sophisticated RNN model, to overcome the mentioned vanishing gradient problem by utilizing LSTM cells.


This repository contains scripts for text generation tasks using TensorFlow. It includes:

- A link to the Shakespeare dataset hosted at 'https://storage.googleapis.com/download.tensorflow.org/data/shakespeare.txt'.
- Scripts for generating LaTeX codes, both simple and complex, using a language model.
- Additionally, the repository features a process where baby names are randomly selected and saved into a text file.
- Utilization of a Simple LSTM, a type of Recurrent Neural Network (RNN), for text generation tasks.

