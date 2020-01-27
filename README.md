# Salesken.ai-Assesment
Problem - 1
Identifying the mis-spelled city names in the dataset and returning the correct unique ids corresponding to the cities
I have used fuzzy wuzzy module to extract and return the highest matching pair of misspelt and correct city names

Problem - 2
To compare the similarity between two sentences lexically as well as semantically I have used word embeddings of GLoVE of 50 dimensions and compared the similarity of the embedding words in sentences using the similarity metric cosine similarity. There are many other methods which give better results than the one I have tried. This can be extended by using BERT embeddings, embbeddings + Earth mover distance, embeddings + Latent Dirchlet Allocation + Jennsen Shanon Distance. Due to time constraint these could not be given a try
