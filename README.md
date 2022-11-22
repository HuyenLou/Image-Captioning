# Image-Captioning
Image Captioning is the task of describing the content of an image in words. This task lies at the intersection of computer vision and natural language processing. Most image captioning systems use an encoder-decoder framework, where an input image is encoded into an intermediate representation of the information in the image, and then decoded into a descriptive text sequence.
## Dataset
Dataset we use is  dataset UIT-ViIC. UIT-ViIC consists of 19,250 Vietnamese captions for 3,850 images. Here is the link to dataset: https://arxiv.org/abs/2002.00175
## Model
Encoder: Image Dataset -> CNN -> Feature vector

Caption -> Word Embeding Vector

Encoder + Word Embedding Vector -> Decoder (LSTM +Attention)

