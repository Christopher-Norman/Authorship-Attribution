# README explaining the code structure and to run models.
This repository attempts to train models using PyTorch for Authorship Attribution to show a learnable relationship for attributing song lyrics.
All code was run in a *Google Colab* environment and imports are defined within the notebooks.
The entire repository can be viewed https://drive.google.com/drive/folders/1SJ2ZPETS3YqeeR37LvadVWLR-qIF0pu9?usp=sharing

## Notebook Structure
First models are trained on a dataset known to work for authorship attribution, the IMDB62 dataset containing 62 IMDB movie review authors
The IMDB dataset is preprocessed in "IMDB Data Pre-processing and Evaluation"
The IMDB models created are trained in "IMDB \*modelname\* Model Training"
The IMDB models are evaluated in "IMDB Model Evaluations" to show a learned relationship.
Then, a spotify lyrics dataset is preprocessed in "Lyrics Data Evaluation and Pre-processing"
The models are trained on the data in "Lyrics LSTM and GRU Model Training"
The models are evaluated, results are analyzed, and a demo of the results is given in "Lyrics Model Analysis"

## Attributions
Implementation of models inspired by https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/reports/2760185.pdf
Lyrics dataset found: https://www.kaggle.com/datasets/edenbd/150k-lyrics-labeled-with-spotify-valence
IMDB Dataset found: https://umlt.infotech.monash.edu/?page_id=266

## LINKS to data stored on the cloud:
Cleaned Lyrics Dataset: https://drive.google.com/drive/folders/1laApETmJzHZyLyfe1yBUPeVH7n4KocPT
Cleaned IMDB Dataset: https://drive.google.com/drive/folders/1ZkT70gt9Wn4p69Lo-00_pG2GFn262mjk
Glove embeddings: https://nlp.stanford.edu/projects/glove/
Intermediate formatted embeddings: https://drive.google.com/drive/folders/1aGLTKPbNGTnqEYpHAz-25fdezhtO-WY0 
Preprocessed gensim embeddings: https://drive.google.com/drive/folders/1r3Elpl906z_dhbRL_iVzPGT9gBhkxzLF
Saved Pytorch Dataset classes: https://drive.google.com/drive/folders/1CwP6grwvBCjfDmonerTNj3jAWHYik-q4
LYRICS DATASET: https://www.kaggle.com/datasets/edenbd/150k-lyrics-labeled-with-spotify-valence
IMDB Dataset: https://umlt.infotech.monash.edu/?page_id=266 -> https://www.dropbox.com/s/np1u1hl343gd73m/imdb62.zip
MODELS: https://drive.google.com/drive/folders/1Q6zFu2fYEs3MrBfu5sSNTdsRoI_PoLlz?usp=sharing
