# Intro
CLIP (Contrastive Language-Image Pre-Training) uses a concept of learning directly from raw text about images which leverages a much broader source of supervision.
It has been shown that when image representations are learned from scratch on a dataset of (image, text) pair collected from random sources, the model transfers non-trivially to most tasks and is often competitive with a fully supervised baseline without the need for any dataset specific training. 
On the other hand a convetional computer vision systems is trained to predict a "fixed set of predetermined object categories" which can restrict their generality and usability since additional labeled data is needed to specify any other visual concept.
Both techniques can be leveraged together in many ways. One usefull application can be bank fraud prediction. The vision embeddings can be combined to get an improved image-text mappings and hence a better similarity score. Here we find out the [improvements in zero shot classification](/Improvements_using_a_limited_class_model.ipynb) by using visual embeddings from CLIP and COAT (Co-Scale Conv-Attentional Image Transformers).

# References
https://github.com/openai/CLIP

https://arxiv.org/abs/2103.00020

https://github.com/mlpc-ucsd/CoaT

http://arxiv.org/abs/2104.06399

 
