Python version - 2.x

A project about text classification (on nltk Reuters dataset) with french/german extensions 

Using: Keras, sklearn, nltk


There are multiple ways to extend a model to different languages, one way involves dealing with word embeddings:

- train a model using english word embeddings aligned in a single vector space from [MUSE](https://github.com/facebookresearch/MUSE)
- save the weights of the pretrained model but reinitialize Embedding layer to use different language 
- tune the model
