# Topic Modelling on Manually Collected Unstructured Text
## What it does
This project applies topic modelling to a large set of academic abstracts to uncover the main themes running through the collection. It builds two different topic models and compares how well each one groups the text into coherent themes.

## Why I built it
This was a coursework assignment for my MSc in Artificial Intelligence at the University of Salford.

## Tools used
Python, NLTK, Scikit-Learn, Latent Dirichlet Allocation (LDA), Non-Negative Matrix Factorization (NMF).

## How to run it
1. Clone this repository and install the dependencies.

2. Place the collected abstracts dataset in google drive and copy the file_id into code.

3. Run the preprocessing script to clean and prepare the text.

4. Run the modelling script to build both the LDA and NMF topic models and compare their coherence scores.

## Results
The dataset consisted of 1,988 academic abstracts collected manually from Scopus using Boolean search queries. The topic models achieved a coherence score of 0.4829. The project also checked that results stayed consistent between a cloud environment (Google Colab) and a local Linux environment.
