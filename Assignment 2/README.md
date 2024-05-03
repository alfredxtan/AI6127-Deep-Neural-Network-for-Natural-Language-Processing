This folder contains the codes and final report for the second individual assignment.

**Seq2Seq Model for Machine Translation**

With the provided data processing steps, perform the following tasks:

1. Exerpiment with the GRU-GRU (encoder-decoder) network. Compute the Rouge1 and Rouge2 scores.
2. Experiment with LSTM-LSTM (encoder-decoder) network.
3. Experiment with biLSTM-GRU (encoder-decoder) network.
4. Add an attention mechanism between encoder and decoder in the GRU-GRU network. The attention mechanism works as follows:
   - For each decoder hidden state, compute the dot product between every encoder hidden state.
   - Then, perform softmax across all the encoder hidden states; this will be the attention score.
   - Using their respective attention score as the weights, compute the attention output as a weightedsum of the encoder hidden states.
   - Finally, concatenate the attention output with the current decoder output. This new vector will be used for generating the next token.
5. Experiment with Transformer-GRU (encoder-decoder) network.

Compare and analyze the difference in performances between each model.
