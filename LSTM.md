# LSTM
## Problems with vanilla RNN
- The component of the gradient in direction that correspond to long term dependencies is small
- The component of the gradient in direction that correspond to short-term dependencies is large
- As a result , RNN can easily learn the short term but not the long term dependencies

- In LSTM network is same as a standard RNN except that the summation units in the hidden layer are replaced by memory blocks 
- The multiplicative gates allow LSTM memory cells to store and acess information over a long period of time. there by mitigatin the vanishing gradient problem
- Along with the hidden state vector ht LSTM maintains a memory vector Ct 
- At each time step the LSTM can choose to read from, write to or reset the cell using explicit gating mechanism
- LSTM computes well behaved gradients by controlling the values using the gates
- check the images for proofs
