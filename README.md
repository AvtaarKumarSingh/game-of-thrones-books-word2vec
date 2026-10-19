Game of Thrones Books – Word2Vec

Overview
This project applies **Word2Vec** to the *Game of Thrones* book dataset to learn word embeddings and explore semantic relationships between words using Natural Language Processing (NLP).

Dataset
The dataset contains the text of the *Game of Thrones* books.

[Game of Thrones Books Dataset – Kaggle](https://www.kaggle.com/khulasasndh/game-of-thrones-books)

Technologies Used
- Python
- Gensim
- NLTK
- NumPy
- Pandas

Project Workflow
1. Load and preprocess the book text.
2. Split the text into sentences and tokenize words.
3. Remove stopwords and clean the text.
4. Train a Word2Vec model using Gensim.
5. Explore word similarities and semantic relationships.

Objective
To understand how Word2Vec learns meaningful word representations from textual data and captures relationships between words in the *Game of Thrones* universe.

Getting Started
Install the required libraries:

```bash
pip install gensim nltk numpy pandas
```

Download the dataset from Kaggle and place the book text files inside the `data` directory before running the notebook.

## License
This project is intended for educational and learning purposes. Please refer to the original dataset source for its usage terms.
