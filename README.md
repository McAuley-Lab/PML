# [Personalized Machine Learning](https://cseweb.ucsd.edu/~jmcauley/pml/) Code Workbooks

This repo contains official code workbooks for textbook  [Personalized Machine Learning](https://cseweb.ucsd.edu/~jmcauley/pml/), about following topics:

| Chapter | Topics | Implemented (or Used) Models |
| :---: | --- | --- |
| 2 | Regression and Feature Engineering | Linear Regression (sklearn) |
| 3 | Classification and the Learning Pipeline | Linear Regression (TF, PyTorch), Logistic Regression (TF, PyTorch), Ridge Model (sklearn) |
| 4 | Introduction to Recommender Systems | Similarity-based Recommendation Models |
| 5 | Model-based Approaches to Recommendation | Latent Factor Model (surpirse, TF, PyTorch), BPR (implicit, TF, PyTorch)  |
| 6 | Content and Structure in Recommender Systems | Factorization Machine (pyFM), BPR (TF) |
| 7 | Temporal and Sequential Models | AutoRegression (sklearn), MF (TF), PMC(TF), FPMC (TF) |
| 8 | Personalized Models of Text | BoW, N-Gram, TF-IDF, Ridge Model (sklearn), word2vec (gensim), item2vec (gensim),  |
| 9 | Personalized Models of Visual Data | Visual Compatibility Model (TF),  |
| 10 | The Consequences of Personalized Machine Learning | Latent Factor Model (TF), BPR (implicit) |

For each chapter, we include a `requirements.txt` file and a  jupyter notebook `Chapter_*.ipynb`. To run the code in notebook of chapter i, you need:
 
1. open folder `Chapter_i`;
2. use `pip install -r requirements.txt` to install the packages;
3. run code in `Chapter_i.ipynb`, data will be saved in `Chapter_i/data` folder.

Please submit an issue or send an email to [zhh004@ucsd.edu](zhh004@ucsd.edu), if you have any questions or suggestions.
