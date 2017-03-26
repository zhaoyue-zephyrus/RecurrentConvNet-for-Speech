This repo holds the codes for the paper

> __Recurrent Convolutional Neural Network For Speech Processing__, Yue Zhao, Xingyu Jin, and Xiaolin Hu, to appear in the 42nd IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2017), New Orleans, USA.

# Documentation

## Install kaldi

Clone [Kaldi](https://github.com/kaldi-asr/kaldi). Follow the documentation to build the toolkit. (Remember to install IRSTLM via `./tools/extras/install_irstlm.sh` since the default setting does not include it.)

## Install CNTK
Install [CNTK](https://github.com/Microsoft/CNTK).

## Run experiments on timit
Put the scripts in `timit-scripts/` under egs/timit/s5/ in the Kaldi repository.

Run `./run.sh` to produce a HMM model by tri3 system.

Run `./train_rcnn_tri00.sh` to generate the RCNN model described in our paper.
