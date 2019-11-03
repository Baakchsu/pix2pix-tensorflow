# pix2pix-tensorflow

Based on [pix2pix](https://phillipi.github.io/pix2pix/) by Isola et al.

[Article about this implemention](https://affinelayer.com/pix2pix/)

[Interactive Demo](https://affinelayer.com/pixsrv/)

Tensorflow implementation of pix2pix.  Learns a mapping from input images to output images, like these examples from the original paper:

<img src="docs/examples.jpg" width="900px"/>

This port is based directly on the torch implementation, and not on an existing Tensorflow implementation.  It is meant to be a faithful implementation of the original work and so does not add anything.  The processing speed on a GPU with cuDNN was equivalent to the Torch implementation in testing.

## Setup

### Prerequisites
- Tensorflow 1.4.1

### Recommended
- Linux with Tensorflow GPU edition + cuDNN



## Citation
If you use this code for your research, please cite the paper this code is based on: <a href="https://arxiv.org/pdf/1611.07004v1.pdf">Image-to-Image Translation Using Conditional Adversarial Networks</a>:

```
@article{pix2pix2016,
  title={Image-to-Image Translation with Conditional Adversarial Networks},
  author={Isola, Phillip and Zhu, Jun-Yan and Zhou, Tinghui and Efros, Alexei A},
  journal={arxiv},
  year={2016}
}
```

## Acknowledgments
This is a port of [pix2pix](https://github.com/phillipi/pix2pix) from Torch to Tensorflow.  It also contains colorspace conversion code ported from Torch.  Thanks to the Tensorflow team for making such a quality library!  And special thanks to Phillip Isola for answering my questions about the pix2pix code.
