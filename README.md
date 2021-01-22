In this repo, I apply the techniques I introduced in my report, which can be found at
https://github.com/erkara/Brief-Introduction-to-Deep-Neural-Networks-Mathematical-Foundations

We will work on the Intel Image Classification problem. Data contains around
25k images of size 150 × 150 distributed under 6 categories;

’building’ : 0, ’forest’: 1, ’glacier’ : 2, ’mountain’ : 3, ’sea’ : 4, ’street’ : 5

There are around 14k images in training set, 3k in validation set and 7k for prediction.
I will use one of the most well-known Python machine learning library Pytorch. In this
repo, I design two different architectures. In practical applications, it is very common to
start with a pretrained model. So, in the first one, I implement a transfer learning with
VGG16. I achieved %92.5 test accuracy and reported other results. I also develop a custom 
convolutional neural network and fine tune using the techniques introduced in the report I 
mention above. I obtained %86 testing accuracy with this custom model.
