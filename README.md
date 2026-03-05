# minhash-lsh
Implementation of Min-Hashing and Locality Sensitive Hashing (LSH) on text documents and MovieLens 100k dataset.

# MinHashing and LSH - CSL7110

Implementation of Min-Hashing and Locality Sensitive Hashing on text documents and the MovieLens 100k dataset.

## Summary
- Character and word level k-grams (2-gram, 3-gram)
- Exact Jaccard similarity between documents and users
- Min-Hash signatures with varying number of hash functions
- LSH with band and row experiments
- False positive and false negative analysis

## Dataset
- 4 news articles (D1, D2, D3, D4) in the minhash folder
- MovieLens 100k dataset (u.data) - download from https://grouplens.org/datasets/movielens/100k/

## How to run
- Place D1.txt, D2.txt, D3.txt, D4.txt in a folder called minhash
- Place u.data in a folder called ml-100k
- Run minhash_lsh.ipynb top to bottom

## Requirements
pip install numpy pandas matplotlib
