# [Personalized Machine Learning](https://cseweb.ucsd.edu/~jmcauley/pml/) Code Workbooks

This repo contains official code workbooks for textbook  [Personalized Machine Learning](https://cseweb.ucsd.edu/~jmcauley/pml/), about following topics:

|  | Topics | Implemented (or Used) Models |
| --- | --- | --- |
| Chapter 2 | Regression and Feature Engineering | Linear Regression (sklearn) |
| Chapter 3 | Classification and the Learning Pipeline | Linear Regression (TF), Logistic Regression (TF), Ridge Model (sklearn) |
| Chapter 4 | Introduction to Recommender Systems | Similarity-based Recommendation Models |
| Chapter 5 | Model-based Approaches to Recommendation | Latent Factor Model (surpirse, TF), BPR (implicit, TF),  |
| Chapter 6 | Content and Structure in Recommender Systems | Factorization Machine (pyFM), BPR (TF) |
| Chapter 7 | Temporal and Sequential Models | AutoRegression (sklearn), MF (TF), PMC(TF), FPMC (TF) |
| Chapter 8 | Personalized Models of Text | BoW, N-Gram, TF-IDF, Ridge Model (sklearn), word2vec (gensim), item2vec (gensim),  |
| Chapter 9 | Personalized Models of Visual Data | Visual Compatibility Model (TF),  |
| Chapter 10 | The Consequences of Personalized Machine Learning | Latent Factor Model (TF), BPR (implicit) |

For each chapter, we include a `requirements.txt` file and a  jupyter notebook `Chapter_*.ipynb`. To run the code in notebook of chapter i, you need:
 
1. open folder `Chapter_i`;
2. use `pip install -r requirements.txt` to install the packages;
3. run code in `Chapter_i.ipynb`, data will be saved in `Chapter_i/data` folder.

Please submit an issue or send an email to [zhh004@ucsd.edu](zhh004@ucsd.edu), if you have any questions or suggestions.