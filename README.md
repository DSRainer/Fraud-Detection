This GAN Model is trained on a Tensorflow Dataset for Fashion Images that have a variety of items like Clothes, Accessories, Shoes, etc.
To build this model, I first built the Generator model and the Discriminator Model
Then, wrote a custom Model function with a custom fit and compile function to loop the Generator and Discriminator in a Loop
The Generator is rewarded when it successfully manages to fool the Discriminator.
The Discriminator is rewarded when it successfully tells a fake from a generated image.
Since my computer cannot run 2000 epochs with the required GPU for this task, I used a pretrained model for 2000 epochs and used it to generate the images. 
