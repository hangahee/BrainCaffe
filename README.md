# BrainCaffe

This is a repository for building Caffe for Brain servers.

Step 0. Install required libraries
  - MKL or OpenBLAS, etc...
    - Installing OpenBLAS: get source from https://github.com/xianyi/OpenBLAS/archive/v0.2.19.zip, and run "make" and "sudo make install"
    - install glog from https://github.com/google/glog/releases/tag/v0.3.4  => done by running external.sh in external folder
  - Matlab may be very useful with MatCaffe!
  - See [Ubuntu_setup.txt](./Ubuntu_setup.txt) for detail info on setting Ubuntu servers

Step 1. Get Caffe code: 
  Download official Caffe code from https://github.com/BVLC/caffe.
  - Option 1. RC 3 version: https://github.com/BVLC/caffe/archive/rc3.zip
  - Option 2. Get the latest master version.

Step 2. Use these Makefile and Makefile.conf to build a Caffe.
  - run "./cprc3.sh" to copy those files to ../caffe-rc3
  
Then, enjoy!
