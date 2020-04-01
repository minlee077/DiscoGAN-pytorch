# DiscoGAN-pytorch

PyTorch implementation of [Learning to Discover Cross-Domain Relations with Generative Adversarial Networks](https://arxiv.org/abs/1703.05192).

<img src="./assets/model.png" width="80%">

## Results

### Shoes2handbags dataset

`x_A` -> `G_AB(x_A)` -> `G_BA(G_AB(x_A))` (shoes -> handbag -> shoes)

<img src="assets/DiscoGAN-shoes2bagsA-21.png">

`x_B` -> `G_BA(x_B)` -> `G_AB(G_BA(x_B))` (handbag -> shoes -> handbag)

<img src="assets/DiscoGAN-shoes2bagsB-21.png" >

`Losses`

<img src="assets/DiscoGAN-shoes2bagss2b_loss_figure.png" width="40%"> <img src="assets/DiscoGAN-shoes2bags-recon_loss_figure.png" width="40%"> 
