# Tumor Segmentation Playground

Interactive U-Net simulator for medical image segmentation,
inspired by TensorFlow Playground.

**Live Demo:** https://kullaniciadi.github.io/tumor-segmentation-playground

## Features
- Real-time training simulation with loss/Dice/HD95 curves
- 30+ tunable parameters: architecture, loss function,
  activation, optimizer, augmentation
- Run history table with cross-run comparison
- Tumor scenarios: Glioma, Meningioma, Multi-focal,
  Micro-lesion, Ring-enhancing

## Parameters
- Architecture: U-Net, Attention U-Net, ResU-Net, U-Net++,
  TransUNet, SegNet
- Loss: Dice, BCE, Combo, Focal, Tversky, Lovász, Boundary
- Activation: ReLU, Leaky ReLU, ELU, SELU, GELU, Swish,
  Mish, PReLU
- Metrics: Dice Score, IoU, HD95, Precision, Recall

## Disclaimer
This is an educational simulator. Training curves are
statistically modeled — not a real PyTorch/TensorFlow model.
