# Lab 2 - NLP Rule-Based, Regex, and Word Embedding

## Objective:
The main goal of this lab is to explore and gain experience with NLP rule-based methods, Regex, and word embedding techniques.

## Part 1: Rule-Based NLP and Regex
- We used Regex in Python to generate a structured bill from a user-provided text string.
- Example use case:
    "I bought three Samsung smartphones for 150 $ each, four kilos of fresh banana for 1,2 dollar a kilogram, and one hamburger for 4,5 dollar."
- Generated bill format:
    | Product           | Quantity | Unit Price | Total Price |
    |-------------------|----------|------------|-------------|
    | Samsung smartphone| 3        | 150 $      | 450 $       |
    | Banana            | 4        | 1,2 $      | 3,2 $       |
    | Hamburger         | 1        | 4,5 $      | 4,5 $       |

## Part 2: Word Embedding
- We applied various techniques on the dataset collected during Lab 1:
    - **One-Hot Encoding**, **Bag of Words**, and **TF-IDF** for vectorization.
    - **Word2Vec** approach using both Skip Gram and CBOW models.
    - **GloVe** and **FastText** approaches for advanced word embeddings.
- We used the t-SNE algorithm to plot and visualize the encoded and vectorized data to evaluate the different approaches.
- General conclusions were drawn based on the performance of each method.

## Tools Used:
- **Google Colab**/**Kaggle**/**Jupyter Notebook** for coding and data exploration.
- **Spacy**, **NLTK**, and **Sklearn** for NLP tasks.
- **GitLab**/**GitHub** for version control and project documentation.

## Conclusion:
This lab provided valuable hands-on experience with rule-based NLP, Regex, and word embedding methods. It enhanced our understanding of how different techniques can effectively transform and analyze text data, and allowed us to compare the strengths and limitations of various methods through t-SNE visualization.
