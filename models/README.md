# Models

- Pix2pix: [`pix2pix/`](pix2pix)
- Coupled GAN: [`CoGAN/`](CoGAN)
- Dual GAN: [`DualGAN/`](DualGAN)
- Cycle GAN: [`CycleGAN/`](CycleGAN)
- Spatial Correlative Loss: [`F-LSeSim/`](F-LSeSim)

## Run on our dataset

The dataloader should be modified to use other datasets, like [horse2zebra](https://www.kaggle.com/datasets/balraj98/horse2zebra-dataset) or [selfie2anime](https://paperswithcode.com/dataset/selfie2anime).

Specifically, 
- For Pix2pix, you also need to manually pair the images;
- For CoGAN, you also need to modify the network to fit higher resolution;
