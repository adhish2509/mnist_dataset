# MNIST
The MNIST database of handwritten digits has a training set of **60,000** examples, and a test set of 10,000 examples


# Files

Four files are available:

-   train-images-idx3-ubyte.gz: training set images (9912422 bytes)
-   train-labels-idx1-ubyte.gz: training set labels (28881 bytes)
-   t10k-images-idx3-ubyte.gz: test set images (1648877 bytes)
-   t10k-labels-idx1-ubyte.gz: test set labels (4542 bytes)

## Set file paths based on added MNIST Datasets

For instance,
input_path='C:\Humber\AI Capstone\mnist'

training_img_path = join(input_path, 'train-images-idx3-ubyte/train-images-idx3-ubyte')
training_label_path = join(input_path, 'train-labels-idx1-ubyte/train-labels-idx1-ubyte')
test_img_path = join(input_path, 't10k-images-idx3-ubyte/t10k-images-idx3-ubyte')
test_label_path = join(input_path, 't10k-labels-idx1-ubyte/t10k-labels-idx1-ubyte')

## Run the Code

*Important*
!pip install mlxtend
