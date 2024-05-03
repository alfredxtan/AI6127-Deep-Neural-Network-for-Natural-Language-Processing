This folder contains the source codes and the final report for the first individual assignment. 

**Deep Learning models for Sentiment Classification**

1. Experiment with different optimizers, including SGD, Adam and Adagrad
2. Using Adam optimizer, conduct experiments using simple RNN, experiment with different number of epochs training: 5, 10, 20, and 50.
3. Use a pretrained Word2Vec embedding, together with Adam optimizer and 50 epochs training, compare against the performance of model in task 2. The pretrained embedding can be found [here](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=s
haring).
4. Fix Adam optimizer, 50 epochs, and randomly initialized embedding, and try the following models:
   - Single-layer FFN (hidden dimension = 500)
   - Two-layer FFN (hidden dimensions = 500 and 300)
   - Three-layer FFN (hidden dimensions = 500, 300 and 200)
   - CNN (feature maps sizes of 1, 2, and 3)
   - LSTM
   - Bi-LSTM
  Compare and discuss the performance differences between each model.
