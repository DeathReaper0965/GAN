# GAN

It uses the concept of generator and discriminator as a deconvolutional and convolutional neural networks respectively along with other pooling and activation functions to generate random data which is very closely related to the original data used for testing and training from literally from nothing provided to the generator network.

The weights gets updated according to the gradient calculated by the loss functions of both generative and discriminator networks in each iteration. So, the model gets improved gradually after many iterations.

This model outputs the tensor graphs to a local directory, so that we can visualize it using the tensorboard locally to get a better understanding of what is happening in the inner iterations. Due to less computational power(locally) I had to stop the training after 16k iterations. Training the same code over cloud would be a great option in this case.

Discriminator loss on generated values ranging over a number of iterations:


![screenshot from 2018-02-25 11-23-06](https://user-images.githubusercontent.com/11135080/36638636-8654fc9a-1a20-11e8-9fcf-6fdf67e021fc.png)

Discriminator loss on real values ranging over a number of iterations:


![screenshot from 2018-02-25 11-22-54](https://user-images.githubusercontent.com/11135080/36638637-86813742-1a20-11e8-9ca6-c851211a1e77.png)
