# promoter-detection
Promoter detection of DNA sequences using Transformers from scratch and [DNABERT](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwja_6rkptWCAxV-1gIHHdLQCuoQFnoECAoQAQ&url=https%3A%2F%2Fgithub.com%2Fjerryji1993%2FDNABERT&usg=AOvVaw1pGwuVjrAQumbOsG5bkdgj&opi=89978449).

Emmanouil Chatzakis, emmanouil.chatzakis@epfl.ch

## Overview
This main part of the work is gathered in the provided notebook file. The notebook contains three parts:
- Part 1: In part 1, positional encoding and self-attention for transformers are implemented from scratch, and evaluated on some small data.
- Part 2: In part 2, promoter detection is implemented using BERTFromMaskedLM, utilizing the positional encoding and self-attention from part 1. Promoter detection is a classification of DNA sequences to the classes "contain" or "not contain" a promoter.
- Part 3: In part 3, promoter detection is implemented using DNABERT instead of transformers created from scratch. Specifically, we show that using the DNABERT foundation model, we manage to achieve an accuracy of almost 90% using only 5k DNA sequences for training and testing.

## About
Part of the code and data were provided by [BRBIC LAB of EPFL](https://brbiclab.epfl.ch/), as part of the 3rd assignment of the Machine Learning in Biomedicine course. 
