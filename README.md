# Art DCGAN in Keras
WIP of Robbie Barrat's Art DCGAN in Keras.

# Inspiration
Since Torch is an utter nightmare to install on Windows, here's a Keras implementation of Barrat's Art DCGAN

The code was originally [Jason Brownlee's CIFAR10 GAN](https://machinelearningmastery.com/how-to-develop-a-generative-adversarial-network-for-a-cifar-10-small-object-photographs-from-scratch/) before I butchered it

The topology of the Discriminator and Generator are from [Barrat's Art DCGAN](https://github.com/robbiebarrat/art-DCGAN)

# Usage
Currently, images MUST be 128x128

python keras-art-dcgan.py -dataset=datasetname

Image data should all be in /data/datasetname


# To do
This is very heavily a WIP!

- Let user define hyperparameters
- Dynamic image input size

# Have fun!
I'd love to see what you generate using this, please post your synthesised images!

Cheers,
Jordan J. Bird
http://jordanjamesbird.com/
