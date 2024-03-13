# MonetArt

## Introduction
Leveraging StyleGAN-generated synthetic data to enhance CycleGAN training for improved style transfer and domain adaptation.

Read the whole paper: https://drive.google.com/file/d/1sxdXZG1O8eYnPzWo06DNIt54mIyRadLd/view

## Generate Monet-style Paintings with StyleGAN
Download our pre-trained StyleGAN: https://drive.google.com/file/d/1qS9mjdYWLoCnMR1Wk6SmXlCeZ-4iwrVl/view

then you can generate synthetic Monet-style paintings

```
cd StyleGAN

python gen_images.py --outdir=output --trunc=1 --seeds=0-49 --network='network-240kimg.pkl'
```

## Implementation of CycleGAN
Check our implementation of CycleGAN: https://colab.research.google.com/drive/1bEoEZe4k5k4MqBd0keHnW0so3AfmhU1z?usp=sharing

Feed the synthetic data into CycleGAN as training data, and train CycleGAN.

## Result
Synthetic data is better than real data because it learns representative features and is more diverse.
