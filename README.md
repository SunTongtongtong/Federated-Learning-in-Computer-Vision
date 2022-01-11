# Federated-Learning-in-Computer-Vision

## Transformer Based Framework：

## Data Share:
**FedCG:Leverage Conditional GAN for Protecting Privacy and Maintaining Competitive Performance in Federated Learning** upload classifier and generator for each client. The server merge the generators and send back.

**FedProto: Federated Prototype Learning across Heterogeneous Clients**
Upload prototype instead of model gradients, prove to converge. Loss setting have a regularization between the server global prototype can client local prototype. The experiments are based on easy cnn nets, i.e, 2 CNN layers and 2 FC layers. 

**No Fear of Heterogeneity: Classifier Calibration for Federated Learning with Non-IID Data， NeurIPS2021**
Finding the classifier is the key part that distribute differently between different clients. 
The paper proposed to alignment classifiers among clients based on generated virtual representations. So federated learning first, and do the alignment afterwards. 
Based on the mean/variance for each client on feature level, the server recalculate a single mean/variance. And based on a gaussian distribution with server mean/variance, the virtual representation was generated. 


## Personalisation & Generalisation：
**On Bridging Generic and Personalized Federated Learning**
upload hypernet for each client, and the hypernetwork is used to generate client personalised model weight. 

## Server model generalisation
