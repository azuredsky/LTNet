# LTNet
Implementation of LTNet in "Facial expression recognition with inconsistent datasets", ECCV 2018 

# Preparation
- Data: 
  Please download the cifar10 dataset from https://www.cs.toronto.edu/~kriz/cifar.html.
For convience, we have updated our used images to [OneDriver](https://1drv.ms/u/s!AlRHUFATbq96cnlNGeuebUsX7Fw)

- Caffe: Please download the current [CAFFE](http://caffe.berkeleyvision.org/). Then, add the extra layers in folder "[add to caffe](https://github.com/dualplus/LTNet/tree/master/add_to_caffe)" and recompile Caffe.

# Train LTNet
- Change the "source" and "root_folder" to the path in your computer.
- run "sh run_mixture.sh" to pretrain the model
- run "sh run_LTNet.sh" to train LTNet.
