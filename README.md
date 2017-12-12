# Tensor RNN
Source code for tensor recurrent neural network (TRNN)

[Paper](https://arxiv.org/abs/1711.00073)
[NIPS post](http://roseyu.com/Materials/nips17-tsw-poster.pdf)


improving vanilla RNN w.r.t

1. high-order Markov process

2. high-order interactions in hidden states

3. dimension reduction with tensor network model

files
- reader.py 
read the data into train/valid/test datasets, normalize the data if needed

- model.py
seq2seq model for sequence prediction

- trnn.py
tensor-train lstm cell and corresponding tensor train contraction

- trnn_imply.py
forward step in tensor-train rnn, feed previous predictions as input
