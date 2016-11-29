Clusteror
=========
* Unveils internal "invisible" patterns automatically
* https://github.com/enfeizhan/clusteror
* Fei Zhan
* License: Public Domain

This is a tool for discovering patterns existing in a dataset. It can be useful
in segmenting customers based on their demographic, geographic, and past
behaviours in a commercial marketing environment. Users are encouraged to
adventure with it in other scenarios.

Under the hood, a pretraining of 
[(Stacked) Denoising Autoencoder](https://en.wikipedia.org/wiki/Autoencoder)
is implemented in
[Python deep learning](http://deeplearning.net/tutorial/) library
[Theano](http://deeplearning.net/software/theano/). Therefore, an installation
of Theano is mandate. About how to install Theano, please read
[Theano installation guide](http://deeplearning.net/software/theano/install.html).

If you are lucky to have Nvidia graphic card, with proper setup Theano can
parallel the calculation to be able to scale up to large datasets.