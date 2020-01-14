# Art DCGAN in Keras
WIP of Robbie Barrat's Art DCGAN in Keras.

## Inspiration
I didn't know how GANs worked, and I wanted to know how GANs worked... oh, [*and that AI painting sold for $432,500*](https://www.christies.com/features/A-collaboration-between-two-artists-one-human-one-a-machine-9332-1.aspx).

Since Torch is an utter nightmare to install on Windows, here's a Keras implementation of Barrat's Art DCGAN

The code was originally [Jason Brownlee's CIFAR10 GAN](https://machinelearningmastery.com/how-to-develop-a-generative-adversarial-network-for-a-cifar-10-small-object-photographs-from-scratch/) before I butchered it

The topology of the Discriminator and Generator are from [Barrat's Art DCGAN](https://github.com/robbiebarrat/art-DCGAN)

Model based on [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434) (2015 preprint, Radford, et al.)

## Usage
Currently, images MUST be RGB and 128x128

python keras-art-dcgan.py -dataset=datasetname

Image data should all be in /data/datasetname

## Requirements
- Keras
- Tensorflow (or Theano if you switch it to channels last)
- NumPy
- Pillow
- progressbar


## To do
This is very heavily a WIP!

Wishlist:
- Let user define network hyperparameters
- Dynamic image input size
- Allow images of only one colour channel
- Figure out a better topology for faster learning
- Figure out a better topology to prevent failure cases (eg. losses hitting 0 and training ceasing)
- Figure out whether I actually have implemented Barrat's topology completely, if someone who knows Torch can correct me and make a PR then please do

## Have fun!
I'd love to see what you generate using this, please post your synthesised images!

Cheers,

Jordan J. Bird

http://jordanjamesbird.com/
