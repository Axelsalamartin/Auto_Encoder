# Auto Encoder (AE) :

This model is able to recreate the input. 
It is often used to recreate images which are noisy or blurry.. It can also be linked with compressed search systems.

Here we will be recreating images of the MNIST dataset.
We will compress the 784 pixels images down to 64 values only.

## How does it works ?

The first part is to encode the input to create a compressed version of it. 
Then there is the decode part where it recreates an output from the compressed version.
The sentence often used about this type of algorithms (also GAN) is : "I can not create what I don't understand."
So as it says the model learns what are the important features and how to encode and decode them. 

To go further, trying a Variation Auto Encoder (VAE) to create variations of the provided data could be nice. I do this using a Generative Adversarial Network(GAN) here : 
https://github.com/Axelsalamartin/GAN

Here is a link to an AE trained on pokemons :
https://hackernoon.com/how-to-autoencode-your-pok%C3%A9mon-6b0f5c7b7d97
The interesting thing here is that the encoding downsample each pokemon down to only 4 values. So the model is able to recreate the original pokemon of 12288 values(64x64 RGB images) based on only 4 !
