# MonetArt

## Introduction
Leveraging StyleGAN-generated synthetic data to enhance CycleGAN training for improved style transfer and domain adaptation.

## Generate Monet-style Paintings with StyleGAN
Download our pre-trained StyleGAN: https://drive.google.com/file/d/1qS9mjdYWLoCnMR1Wk6SmXlCeZ-4iwrVl/view, then you can generate synthetic Monet-style paintings

```
cd StyleGAN

python gen_images.py --outdir=output --trunc=1 --seeds=0-49 --network='network-240kimg.pkl'
```
