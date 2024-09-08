# AryansICGMindfulPick


# Abstract
The datasets related with FMCG goods are essential in quickly identifying reviews about various common goods in the market including Packaged foods,Beverages etc. especially in the largely growing markets nowadays. Our model mainly deals with the recognition of texts on the product (after uploading the image) followed by the revelation of the review responses. The FMCG product we worked for are  Beverage,Wine, Beer & Liquor,Beer
# What is spaCy?

SpaCy is a library for Natural Language Processing that can process and “understand” large volumes of text.
# What’s a Vocab?

Strings take a lot of space to store, so spaCy stores them as hash-values instead. Since the hash values hold no meaning on their own, the conversion between them is stored in Vocab.
Vocab is sort of like a translator between the hash values and the words.
# What does the spaCy model do?

As soon as the model is called on a text, it puts the text through a preprocessing pipeline. A preprocessing pipeline is a series of steps (functions) that the model performs to “understand” the text and prepare it for further processing.
 


# Changing the pipeline
A very practical feature of spaCy is that it allows you to modify the pipeline. You can add steps (functions) that process the doc as you desire.
The vector() accesses the vector representations of the entire sentences after the word embeddings and similarity() method calculates the cosine similarity between the vectors of the two sentences.




# About Image Recognition Task:
For image recognition purposes we used the PP-OCR model.

(a)About PP-OCR…
PP-OCR is a self-developed practical ultra-lightweight OCR system which is a two-stage OCR system, in which the text detection algorithm is DB(differentiable binarization), and the text recognition algorithm is SVTR(Scene Text Recognition with a Single Visual Model). Besides, a text direction classifier is added between the detection and recognition modules to deal with text in different directions.
 
Differential Binarization is a method that inserts the binarization operation into a segmentation network for joint optimization. In this manner, the threshold value at every place of an image can be adaptively predicted, which can fully distinguish the pixels from the foreground and background.
But standard binarization function is not differentiable so this method uses an approximate function of standard binarization function named Differential Binarization which is fully differentiable when training using it along with a segmentation network.
SVTR introduces transformers structure, which can mine the context information of text line image more effectively, so as to improve the ability of text recognition.

(b)What Pipeline does it follow?
PP-OCR adopts 19 effective strategies from 8 aspects including backbone network selection and adjustment, prediction head design, data augmentation, learning rate transformation strategy, regularization parameter selection, pre-training model use, and automatic model tailoring and quantization to optimize and slim down the models of each module.
 

# Testing the model…
On certain standard benchmarks, PP-OCR generates quite accurate results.

# DATASET
Dataset had a collection of various information about beer,liquor and wine.
https://data.world/datafiniti/wine-beer-and-liquor-reviews/workspace/file?filename=wine+reviews.csv
# DATASET PREPROCESSING
It invloved reemoving the irrelevant columnss from the dataset including product id, links etc.

Installing required packages 

pip install -r requirements.txt



.
