# Generative-Adverasial-Network
A side project of MOOC "Intro to deep learning" by Higher School of Economic.
In this project, I made a simple DCGAN base on the original document of GAN, you can find more information here:
https://arxiv.org/abs/1406.2661

You can find the dataset which was used in this project from here:
- http://www.cs.columbia.edu/CAVE/databases/pubfig/download/lfw_attributes.txt
- http://vis-www.cs.umass.edu/lfw/lfw-deepfunneled.tgz
- http://vis-www.cs.umass.edu/lfw/lfw.tgz

Here is the result after 15000 iterations(it took about 6 hours in my computer):
![Result](https://github.com/tvthanh95/Generative-Adverasial-Network/blob/master/index.png)

The result isn't great because the model of generator is too simple(due to limition of my computer memory) and I didn't use some powerful techniques(batch norm or dropout).
