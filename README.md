# CycleGANs
A notebook reflecting the CycleGAN paper in code

## Coded in Tensorflow
- Used tf.data to boost the process in GPU
- dataset used from inbuild tensorflow_dataset's dataset (monet2photo)
- approximately 130 sec's to run 1 epoch when using batches of 4
- image size used is 256x256x3
- checkpoints are created at every **5 epochs**, if you don't want to train from scratch then you can use the checkpoint provided [here](https://drive.google.com/drive/folders/1XldhnxrzUg_OCGjb3FSmgZsgYF2lDtjG?usp=sharing)

## Prerequisites
- pip install tensorflow-dataset
- pip install tensorflow-addons
- Nvidia GPU is prefered to train efficiently

## References
- [Oringinal implementation in Pytorch](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
- [Original Paper](https://arxiv.org/abs/1703.10593)
- [Medium article](https://medium.com/analytics-vidhya/transforming-the-world-into-paintings-with-cyclegan-6748c0b85632)
