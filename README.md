# Novel-CNN-Architecture-with-Residual-Learning-and-Deep-Supervision
Abstract:
One of the most investigated methods to increase the accuracy of convolutional neural networks (CNN) is by increasing its depth.
However, increasing the depth also increases the number of parameters, which makes convergence of back-propagation very slow
and prone to overfitting. Convolutional networks with deep supervision (CNDS) add auxiliary branch to addresses the problem 
of slower convergence and overfitting. However, CNDS does not resolve the issue of degradation, which can be addressed 
by residual learning. In order to effectively train deep neural networks, in this paper, we propose Residual-CNDS network,
which adds residual learning to CNDS. Residual connections are parameter free and add only negligible amount of computation, 
thereby it has very little impact over complexity of the network. Results of our experiments on very large-scale MIT Places 205
scene dataset support our hypothesis that adding the residual connections to the CNDS will enhance the accuracy of the network.
Our experiments show that the proposed network improves upon other recently introduced state of the art networks both in terms
of top-1 and top-5 classification accuracy.
