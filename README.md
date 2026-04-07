**Bangla Text Generation using LSTM (PyTorch)**

**Project Overview**

This project focuses on generating Bangla text using a deep learning model called LSTM (Long Short-Term Memory). The model learns patterns from Bangla poetry and then generates new text that looks similar in style. The dataset used in this project is based on famous poems by Rabindranath Tagore, which helps the model learn meaningful and artistic Bangla language patterns.

**Objective**

The main goals of this project are:

    Learn how sequence models work on real text data
    Understand character-level text generation
    Implement an LSTM model using PyTorch
    Generate Bangla text automatically

**Why LSTM?**

Bangla language has complex structure:

    Characters combine with vowel signs (মাত্রা)
    There are joint characters (যুক্তাক্ষর)
    Long-range dependencies exist in sentences

Traditional RNNs struggle with these problems due to vanishing gradients.

LSTM solves this by using:

    Memory cells
    Gates (input, forget, output)

This allows the model to remember long-term patterns in text.


**Dataset**

The dataset is created using multiple Bangla poems written by Rabindranath Tagore.
To improve training, the text is repeated several times to increase data size.

**Output**

The model can generate Tagore-style Bangla text such as:

    Poetic sentences
    Rhythmic structures
    Meaningful word patterns
