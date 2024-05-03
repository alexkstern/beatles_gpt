# Beatles GPT

This tutorial delves into the paper "Attention is All You Need" by Vaswani et al., which can be found [here](https://arxiv.org/abs/1706.03762). Introduced in 2017, this paper revolutionized natural language processing by presenting the transformer architecture. Our focus will primarily be on the decoder component of the transformer, providing a detailed look at its internal mechanics. The content of this tutorial is inspired by Andrej Karpathy's practical implementation, which is thoroughly explained in [this Colab Notebook](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing). We do a step-by-step walkthrough of a single forward pass in this notebook. Note that this tutorial does not cover training on the Beatles text dataset; it is focused solely on explaining the functionality of the model.

To set up your environment for this tutorial, install torch using pip, or install the requirements.txt:

```
pip install torch
```
