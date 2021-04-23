# NLP project - Combining Supervised and Unsupervised Methods for Keywords Extraction - ENSAE - Tom Guédon & Elias Chaumeix

__The aim of this project is to extract keywords from a short text.__ For this purpose we used abstracts of research papers and the associated keywords. Our dataset is the Scielo website that we scrapped. It is a Latin American website that publishes articles in English shared by the Sao Paulo Research Foundation and the Latin American and Caribbean Center on Health Sciences Information. In this project, we chose to combine two different approaches : supervised and unsupervised learning. It seemed interesting to us because it is not usual to have access to the actual keywords of the abstracts, most of the time keywords extraction is dealt with unsupervised learning.


## The files
`df.csv` is the abstracts database we extracted 

`NLP_Project (1)` is our main code

`NLP_Keywords_Extraction` is our report where we develop our approach 


The code is pretty heavy so here is the link to our Google Colab : https://colab.research.google.com/drive/1rMzOb7v80usva4-_31Io_wzN4-4G9wyX#scrollTo=qUxN-e99rOoN


## Links to some databases we used
The following databases are too heavy to share them directly. Therefore there are the links to download them if needed. However the code and outputs are already run on our GitHub notebook. 

The following link is the wikipedia database that we used in our notebook : 
https://wikipedia2vec.github.io/wikipedia2vec/pretrained/?fbclid=IwAR33wgCCNJLZKhkBs5k-og83rYj92SYwpsuRK11X97eQHipVkhmSqTlnhNE
We took the enwiki_20180420 (window=5, iteration=10, negative=15) 100d.txt file.

The following link is the question database used for the IDF
https://www.dropbox.com/s/npidmtadreo6df2/data.zip?file_subpath=%2Fdata
We took the train data. 

