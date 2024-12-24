We know that a VAE normally consists of an encoder-decoder architecture. The encoder is the part of the model with layers with consecutively lesser no. of neurons (for eg. [200, 100, 50, ..]) and the decoder has layers with increasing number of neurons. The encoder is said to downsample i.e. reduce the dimensionality of the input, turning it into a somewhat condensed form; and the decoder is said to upsample (expand the dimensions)