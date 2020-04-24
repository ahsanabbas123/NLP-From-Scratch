# NLP-From-Scratch
Pytorch Notebooks

### Basic Sequence to Sequence Learning with Neural Networks [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ouQJVR1HUeUXrh8AbJGmM_v11rRbXMFD)
- The most common sequence-to-sequence (seq2seq) models are encoder-decoder models, which commonly use a recurrent neural network (RNN) to encode the source (input) sentence into a single vector. In this notebook, we'll refer to this single vector as a context vector. We can think of the context vector as being an abstract representation of the entire input sentence. This vector is then decoded by a second RNN which learns to output the target (output) sentence by generating it one word at a time. 
- Dataset : Multi30k
 
### Classifying and Generating names using Character Level RNN 

- Preprocessing at a low level without torchtext. 
- [Dataset](https://download.pytorch.org/tutorial/data.zip)    
- Classification Task [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JZ8G054iHjGgv8Ub3zt7X_3cR3QFrk6e)    
- Generation Task     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10xdiIusBsy87d6CIkQzO3c2q2fD7wd77)

In the following figure from the classification task, bright spots off the main axis that show which languages it guesses incorrectly, e.g. Chinese for Korean, and Spanish for Italian. It seems to do very well with Greek, and very poorly with English (perhaps because of overlap with other languages).
<p align = "center">
  <img src="https://pytorch.org/tutorials/_images/sphx_glr_char_rnn_classification_tutorial_002.png" width="400">
</p>

  
