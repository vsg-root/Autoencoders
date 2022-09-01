# Autoencoders


Autoencoders are an unsupervised learning technique in which we use neural networks for the representation learning task. Specifically, we will design a neural network architecture to impose a bottleneck on the network that forces a compressed knowledge representation of the original input. If the input resources were independent of each other, this compression and subsequent reconstruction would be a very difficult task. However, if there is some kind of structure in the data (i.e. correlations between the input features), that structure can be learned and consequently leveraged by forcing input through the network bottleneck.



![image](https://user-images.githubusercontent.com/108759490/187927789-5c8a1ccd-bb6c-4524-8ef8-408988c9a1c0.png)
