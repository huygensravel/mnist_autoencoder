Author: Huygens Ravelomanana
# Description
We create two different autoencoders for the MNIST data:
1. A Stacked autoencoder with tied weights
2. Convolutional autoencoder:
    + Encoder (conv, maxpool, conv, maxpool, conv, maxpool).
   + Decoder (conv, upsample2d, conv, upsample2d, conv, upsample2d, conv)
   
We then evaluate / "test" the result on unseen data.


