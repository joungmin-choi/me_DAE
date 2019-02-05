# Human cancer classification via representation learning based on denoising autoencoder using DNA methylation profiles
me_DAE is a deep neural network model for cancer type classification based on a high-dimensional DNA methylome dataset. We implemented a multi-layered denoising autoencoder for representative feature learning, and the learned features were further tuned by fully connected layers using a softmax classifier.


## Usage

### Requirements
* Tensorflow
* Python packages : numpy, pandas

### Command
```
python run_me_DAE.py <training_x> <training_y> <testing_x> <testing_y>
```

### Arguments
* ```training_x``` : File of training input dataset with methylation beta values of features
* ```training_y``` : File of cancer class labels for each sample in <training_x>
* ```testing_x``` : File of testing input dataset with methylation beta values of features
* ```testing_y``` : File of cancer class labels for each sample in <testing_x>

*Each dataset file should have header and for class label dataset, they should label each cancer type as 1 and 0 for others.*

## Contact
If you have any question or problem, please send an email to **miniymay@sookmyung.ac.kr**
