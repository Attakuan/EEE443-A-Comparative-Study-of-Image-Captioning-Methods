# EEE443-A-Comparative-Study-of-Image-Captioning-Methods

The purpose of this project is to caption textual descriptions of images by generating sentences that include the states
of objects and the behaviors of people and animals in the corresponding images. The dataset provided by the
instructor contains training and test images along with their captions. The image features are extracted by using
well-known pretrained network which is ResNetV2. Neural network architectures containing Convolutional Neural
Networks (CNNs) and variations of LSTM and GRU recurrent neural networks are utilized to create captions that
capture information about the contents of an image. Furthermore, trainable GloVe 300d and non-trainable GloVe
300d embedding vectors have been utilized to understand the effects of embedding vectors. The training and
validation loss graphs are obtained for each model and their BLEU scores are calculated on the test dataset in order
to compare the performances of the models. Overall, we were able to train and test six networks and compare their
performances in order to decide on the model with the best performance.

## Example Results


![](https://github.com/Attakuan/EEE443-A-Comparative-Study-of-Image-Captioning-Methods/blob/main/ExampleImg.jpg)

![](https://github.com/Attakuan/EEE443-A-Comparative-Study-of-Image-Captioning-Methods/blob/main/ExampleImg2.jpg)

## Installation

It has quite long library installation process. Thus, it is advised that you read the jupyter notebook version of the code where we explained each installation in detail. 


## Contributing

The contributors to this implementation are as follows:

- Atakan Topcu ([linkedin](https://www.linkedin.com/in/atakan-topcu-0a47791b9/))
- Ata Yavuzyılmaz ([linkedin](https://www.linkedin.com/in/ata-yavuzyilmaz/))
- Ata Korkusuz ([linkedin](https://www.linkedin.com/in/ata-korkusuz-77707118b/))
- Dora Tütüncü ([linkedin](https://www.linkedin.com/in/dora-tutuncu-9698b2189/))
