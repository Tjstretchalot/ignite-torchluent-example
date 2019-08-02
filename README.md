# PyTorch Ignite Example

This module is an example of training a convolutional network with PyTorch
ignite on MNIST. This example trains to >99% validation accuracy fairly
consistently. Only the learning rate was tuned.

This repository is meant as a source code reference for small snippets or a
general structure which is helpful, rather than to show off a particular
network architecture.

This uses SGD with a linear cyclic learning rate scheduler. More information
for cyclical learning rates is available at:

[Leslie N. Smith, Cyclical Learning Rates for Training Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7926641)

## Running

`python3 runner.py` to train the model and then `python3 analyze.py` to
generate the video and snapshots with pca3dvis.

Example run output at 'log.txt'

Analysis output: https://youtu.be/492JWqa_epo

## Contributions

If you want to add more comments or clean this up further, you are welcome to
submit a pull request. New features, however, should stay in forked repos,
to keep this one as short as possible. For such forks you may submit a
pull request to this branch updating the readme with a link to the fork
if you explain which feature you added.
