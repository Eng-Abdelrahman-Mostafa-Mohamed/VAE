



# VAE 
VAE(Variation Auto Encoder From Scratch using Py-torch)

# First W Must know What Is Auto Encoder  : Is architicture used to encoding images and reconstruct it may use for image compressing and reconstructing 
but in Generative models could Generate new image only when add
noise into latten space but its very hard to specify what is noise should add to make specefic task like changge the color of hair of people so ..
we have Variation Auto Encoder

. ![image](https://github.com/Eng-Abdelrahman-Mostafa-Mohamed/VAE/assets/116603423/fbb4e9e2-2131-4ce7-9aa2-148b2fa77e1b)

. ![image](https://github.com/Eng-Abdelrahman-Mostafa-Mohamed/VAE/assets/116603423/3b191749-7c28-495a-a306-ee39af913ff8)

As WE see the main diffrence between VAE and AE that in AE we could encode image into latten directly so when we add nois we add into the latten space point directly and that not effecient in gans
ao VAE Use conditional proability to do that and we add somthing call KL diverge when calculate loss 

KL diverge in abstract it use for compairing 2 conditional probabilities and reconstucted loss like MSE or binary cross entropy used for comparing reconstructed image with original image 
