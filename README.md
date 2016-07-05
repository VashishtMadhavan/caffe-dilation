##Caffe for Dilation Network

This is a fork of Caffe that support the training of dilation network described in [this ICLR conference paper](http://arxiv.org/abs/1511.07122). It is updated with the master branch of [BVLC/caffe](https://github.com/BVLC/caffe) at commit [f28f5a](https://github.com/BVLC/caffe/commit/f28f5ae2f2453f42b5824723efc326a04dd16d85) (June 27, 2016). The original README of Caffe is at [README_caffe.md](https://github.com/fyu/caffe-dilation/blob/master/README_caffe.md).

### Build

This fork perserves the compatibililty with vanilla Caffe. For help of compiling this code, please turn to Caffe installation guide.

Makefile in this fork is changed slightly so that the git branch name is appended after $(BUILD_DIR).


### Usage
Please check [fyu/dilation](https://github.com/fyu/dilation/) for how to use this code. The built caffe binary is used directly by [dilation/train.py](https://github.com/fyu/dilation/blob/master/train.py).
