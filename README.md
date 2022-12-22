# CMINet
## Introduction
This is a PyTorch implementation of CMINet for the task of predicting social influence, as described in our paper:
CMINet: a Graph Learning Framework for Content-aware Multi-channel Influence Diffusion

## Package
The code is tested on PyTorch 1.13, pytorch-geometric  2.1.0.

## Datasets
Please download them from the following links.
[Digg dataset](https://www.isi.edu/~lerman/downloads/digg2009.html "Digg dataset")
[Twitter dataset](https://snap.stanford.edu/data/higgs-twitter.html "Twitter dataset")
[Flickr dataset](https://snap.stanford.edu/data/web-flickr.html "Flickr dataset")

## Preprocessing
    python3 preprocess.py  --dataset <dataset-name>

## Train
    python3 train.py --dataset  <dataset> --argfile <file_path>

## Test
    python3 train.py --dataset  <dataset> --task <diffusion/activation> --argfile <file_path>

