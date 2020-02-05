# Machine Translation with RNNs


The useful files for the computation of our project are machine_translation_final.ipynb and the folder "data" which contains the different data we worked on.

## Goal
In this project, we build somes deep neural network for automatic translation. The algorithms accepts English text as input and returns the French translation. The goal is to achieve the highest translation accuracy possible. We found some scores already defined by researchers such as blue scores that we introduced during our presentation.


##### &nbsp;

## Approach
To translate a corpus of English text to French, we need to preprocess our textual data, which includes cleaning, tokenization, padding to use a recurrent neural network (RNN). We tried two principal way of entering the data which are the one hot encoding and the embedding way. We tried different types of layer such as LSTM, dense, GRU, repeatvector, Bidirectional, embedding... and to mix these layers. We tried the created neural networks on different datasets and also on new sentences made with known words. Results were mitigated.

We would have liked to try using already existing embeddeding like WordToVec but we did not have the time to go further on.
