# QNAP-DL

1-click installation for all framework on QNAP Container Station with GPU passthrough

    GPU=nvidia0 gpu-docker run -p 8000:8000 6006:6006 boo0330/qnap-dl

 - [x] Tensorflow:1.10
 - [x] Keras: 2.2.4
 - [ ] Caffe
 - [ ] Caffe2
 - [ ] Theano
 - [ ] MXNet
 - [ ] Pytorch

  
  
Jupyter Notebook:   
`http://IP:8888`

Launch Tensorboard:
Attach your container and execute
`tensorboard --logdir=path/to/log-directory`