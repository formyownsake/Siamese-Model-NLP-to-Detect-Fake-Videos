# Siamese Model NLP to Detect Fake Videos
 A NLP Based Siamese Model Approach to detect Fake videos
 
 (The data used for the model to work is Hidden due to privacy concerns)
 
This Model can determine whether two youtube videos are similar in context or not. 

Use Case of this Model : Once trained, this model can determine if 2 Youtube videos are contextually similar or not. It uses the youtube transcript to contextually compare 2 videos.

Project used :

- Extract transcript of videos from youtube
- Clean Transcripts using NLTK etc.
- Tokenize the transcipts into sequences and create a word index
- Train a word2vec Model in gesim using GoogleNews-vectors-negative300.bin (Google news vectors)
- Convert the video transcript input file into Siamese network Input file.
- Convert Text to word embeddings based on and send to siamese network. The euclidean distance netween 2 videos is the Similarity index.


Concepts Used :

## Siamese Networks :



