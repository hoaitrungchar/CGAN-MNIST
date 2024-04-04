# Description.

This is an implementation of CGAN (Conditional Generative Adversarial Network) for MNIST and Fashion MNIST dataaset. The model is trained on traindataset of MNIST dataset and Fashion MNIST dataset.

## Dataset
This project uses MNIST dataset and FASHION MNIST dataset. 

### MNIST dataset
Contain handwritten digits grayscale images from 0 to 9.
![input_Mnist](https://github.com/hoaitrungchar/CGAN-MNIST-FMNIST/assets/79318706/6519c3d0-4cc9-453a-8582-d985a553c7bb)

### FASHION MNIST dataset
Contain clothes and accessories  grayscale images.
![input_Fmnist](https://github.com/hoaitrungchar/CGAN-MNIST-FMNIST/assets/79318706/4d9eb7a3-a191-46e2-8836-20fccd9056fa)

## Architecture
The architecture of CGAN model based on the architecture in [2]
![image](https://github.com/hoaitrungchar/CGAN-MNIST-FMNIST/assets/79318706/7fb6f2c8-a242-468a-9e22-578a81b73e78)

## Algorithm 
The algorithm to trainning this model based on the Alogrithm 1 in [1] 
![image](https://github.com/hoaitrungchar/CGAN-MNIST-FMNIST/assets/79318706/d01fcbf9-7457-4d8a-b168-8f234e1c6648)

## Result
Here are the reuslt after training models:
### MINST dataset
![output_Mnist](https://github.com/hoaitrungchar/CGAN-MNIST-FMNIST/assets/79318706/e8086f07-dfbd-46b9-b1d1-468eca0060fa)

### FASHION MNIST dataset
![output_Fmnist](https://github.com/hoaitrungchar/CGAN-MNIST-FMNIST/assets/79318706/6e4daa39-9ecb-4c45-8926-d15e71cf5092)

## References
 
[1] Generative adversarial nets Goodfellow, I. J., Pouget-Abadie, J., Mirza, M., Xu, B., Warde-Farley, D., Ozair, S., Courville, A., and Bengio, Y. (2014).

[2] Conditional Generative Adversarial Nets, Mehdi Mirza, Simon Osindero.
