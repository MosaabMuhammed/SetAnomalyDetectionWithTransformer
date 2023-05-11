# Set Anomaly Detection With Transformer
I developed an anomaly detection model using the Transformer Encoder architecture, which was trained to identify an anomalous image from a set of images. 

The implementation involved several steps, including the following:
- Building the Transformer Encoder from scratch and utilizing the CIFAR100 dataset. 
- To extract image features, I utilized a pre-trained ResNet34 model. 
- The input to the transformer consisted of a set of images, one of which was an anomaly, while the remaining images were from the same class.

Moreover, I performed an analysis of the attention weights of the trained model on a correctly labeled example. 

The analysis helped in understanding the model's decision-making process and the contribution of each image to the overall prediction.

Throughout the development process, I leveraged the PyTorch and PyTorch Lightning packages to streamline the development and training of the model. 

Overall, this project demonstrated my expertise in implementing deep learning models and effectively utilizing pre-trained models and attention mechanisms for anomaly detection.
