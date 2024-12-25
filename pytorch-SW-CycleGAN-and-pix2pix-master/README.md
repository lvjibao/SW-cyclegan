# SW-CycleGAN and pix2pix in PyTorch

### SW-CycleGAN train/test
- Train a model:
```bash
python train.py --dataroot ./datasets/train --name maps_cyclegan --model cycle_gan
```
- Test the model:
```bash
python test.py --dataroot datasets/test --name maps_pretrained --model test --no_dropout
```