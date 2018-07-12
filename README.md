# Auto Encoder (AE) :

This model is able to recreate the input. 
This is then often used to recreate image which are noisy or blurry..

Here we will be recreating images of the MNIST dataset.

## How does it works ?

The first part is to encode the input to create kind of a compressed version of it. 
Then there is the decode part where it recreate an output from the compressed version. 
During the training the model learns to compress the most important features of the data so that it can recreate it correctly.
The sentence often used about these types of algorithm (also GAN) is : "I can not create what I don't understand."
So as it says the model learns what are the important features and then encode those specific features to get them back with the decode part. 

Now trying a Variation Auto Encoder (VAE) to create new data could be nice. I do this using a Generative Adversarial Network(GAN) here : 
https://github.com/Axelsalamartin/GAN

Here is a link to an AE trained on recreating pokemons :
https://hackernoon.com/how-to-autoencode-your-pok%C3%A9mon-6b0f5c7b7d97
