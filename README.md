# DL_HW2-VAE-

## Dataset:

1. TibetanMNIST (gray images)
2. Animation faces (RGB images)

## VAE:

1. Convert the gray images into binary images first.

2. Variational posteriors are Bernoulli for binary data and Gaussian for real value data

### Results after training

Animation faces:
<img width="120" alt="image" src="https://user-images.githubusercontent.com/77607182/178141134-badf2142-8231-4e40-8a89-108d3a229488.png">

<img width="200" alt="image" src="https://user-images.githubusercontent.com/77607182/178141146-8cc09058-c8ad-49c2-88a6-2faea85c153e.png">

MNIST dataset:
<img width="120" alt="image" src="https://user-images.githubusercontent.com/77607182/178141168-34abb701-86e0-47e1-b945-4a9d2093fa94.png">
<img width="200" alt="image" src="https://user-images.githubusercontent.com/77607182/178141169-a82ca2d9-ec91-414c-b5aa-1724d223a99e.png">

### Sample the prior p(z) and use the latent codes z to synthesize some examples:

<img width="120" alt="image" src="https://user-images.githubusercontent.com/77607182/178141218-8e2f3d05-eff3-4042-8a08-d384c2334ada.png">
<img width="200" alt="image" src="https://user-images.githubusercontent.com/77607182/178141227-5b14bbd2-66b4-4f71-b09c-2844bdf3ea4f.png">
