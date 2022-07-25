# Biomedical Text Mining using NLP

Named entity recognition (NER) is known as one of the most fundamental tasks in biomedical text mining which aims to automatically recognize and classify biomedical entities such as genes, proteins, chemicals, and diseases from the text. State-of-the-art NER systems often require handcrafted features specific to each entity type, such as genes, chemicals, etc. 

NER identifies new gene names from text. Although recent studies explored using neural network models for NER. NER classifies phrases and references of specific entities in a Text. 

This project of ours is providing a neural network-based multi-task learning framework for named entity recognition. Here the model being used is the hybrid BiLSTM-CRF model. 

The BiLSTM (bidirectional long short-term memory) layer models the context information of each character. The hidden states of the BiLSTM layer are fed into the CRF layer to optimize sequence tagging with the help of adjacent tags. We are using a neural network-based multi-task learning framework. 

Multi-task learning offers a solution by collectively training a model on several related tasks so that each task benefits model learning in other tasks without introducing additional errors . 

MTL is a subfield of machine learning in which multiple learning tasks are solved at the same time while exploiting commonalities and differences across tasks.
