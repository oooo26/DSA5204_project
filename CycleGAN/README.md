# Cycle-Consistent Adversarial Networks (CycleGAN)

Reference: https://github.com/eriklindernoren/PyTorch-GAN#cyclegan

## Run

Example:

```bash
cd data
bash download_cyclegan_dataset.sh monet2photo
cd ..
python cyclegan.py
```

Defaultly, it fits on the monet2photo dataset.
More configures can be checked by:

```bash
python cyclegan.py -h
```
