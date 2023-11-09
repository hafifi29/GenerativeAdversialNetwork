# GenerativeAdversialNetwork
GAN is a battle between two adversaries, the generator and the discrminator.
The generator tries to convert random noise into observations so that it can fool the discriminator into thinking that it comes from the original dataset. The discriminator tries to predict whether an observation is real or fake (generated by the generator).
The key in GAN training is how we alternate the training of the two networks so that the generator makes more realistic observations and fools the discriminator, and the discriminator maintains its quality in distinguishing between real and fake observations.

