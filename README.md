# Natural Language Processing (Exploration)

This project is an exploration into the various aspects of **Natural Language Processing (NLP)**. The aim is to build a portfolio of experiments and learning exercises that serve as references for later review. Throughout this project, I will explore the key techniques and tools used in NLP, from basic string methods to advanced deep learning models for natural language understanding.

The project will cover a broad range of topics and will include practical implementations and experiments using popular NLP libraries like **spaCy**, **NLTK**, and **Scikit-learn**. In addition, I'll implement various models, such as **LDA**, **NMF**, **LSTM**, and more, to solve real-world problems and apply NLP in different use cases.

---

## Contents

1. [Technologies and Tools](#technologies-and-tools)
2. [Key Topics Covered](#key-topics-covered)
3. [Projects](#projects)
4. [Online Resources](#online-resources)
5. [Setup and Installation](#setup-and-installation)

---

## Technologies and Tools

- **spaCy**: A powerful NLP library in Python that simplifies many NLP tasks, from tokenization and dependency parsing to named entity recognition (NER). I use `en_core_web_sm` for small sentence processing and `en_core_web_lg` for word vectors.

  - For detailed info on **dependency parsing**, refer to these links:
    - [Dependency Parsing and Visualization with spaCy](https://medium.com/@alshargi.usa/dependency-parsing-and-visualization-with-spacy-b419b9eda169)
    - [spaCy Linguistic Features](https://spacy.io/usage/linguistic-features)

- **NLTK (Natural Language Toolkit)**: A comprehensive library used for a variety of NLP tasks such as tokenization, stemming, and POS tagging.

- **Scikit-learn**: A popular machine learning library for Python, used for implementing various algorithms like **LDA**, **NMF**, and other clustering and classification algorithms.

- **Gensim**: An open-source NLP library for topic modeling, particularly useful for tasks like **Latent Dirichlet Allocation (LDA)** and **Word2Vec**. It's known for being highly efficient and scalable.

- **VADER**: A lexicon and rule-based sentiment analysis tool that can be used for **semantic and sentiment analysis** tasks.

- **Deep Learning Frameworks**: Various deep learning models for NLP tasks, including **LSTM**, **RNN**, **ANN**, and **GRU**. These are implemented for tasks like **question answering** and **chatbot development**.

---

## Key Topics Covered

1. **String Methods in Python**: Basic string manipulation techniques in Python, which are fundamental for text preprocessing.

2. **NLP Basics**: Introduction to common NLP tasks like tokenization, POS tagging, and named entity recognition (NER).

3. **Introduction to Tools and Methods**: Overview of key libraries like **spaCy**, **NLTK**, and **Scikit-learn**.

4. **Semantic and Sentiment Analysis**: Techniques to determine the sentiment of a text. Sentiment analysis can be used for tasks like analyzing social media posts or customer reviews.

5. **VADER Sentiment Analysis**: VADER (Valence Aware Dictionary and sEntiment Reasoner) is a tool used for sentiment analysis, particularly for social media content. It uses a lexicon and a set of rules to assign sentiment scores.

6. **Topic Modeling**:

   - **LDA (Latent Dirichlet Allocation)**: A topic modeling technique that assumes each document is a mixture of topics, and each topic is a mixture of words.
   - **NMF (Non-Negative Matrix Factorization)**: An alternative to LDA for topic modeling. It's faster and can handle larger datasets.

7. **Deep Learning for NLP**:

   - **LSTM (Long Short-Term Memory)** and **RNN (Recurrent Neural Networks)**: These deep learning models are particularly useful for sequence-based tasks like text generation or machine translation.
   - **GRU (Gated Recurrent Units)**: A variant of LSTM that can be faster and more efficient in some cases.
   - **ANN (Artificial Neural Networks)**: Used for classification and regression tasks in NLP.

8. **Question Answering (QA) Chatbots**: Implementing a chatbot using the **Babi dataset** from Facebook, based on the **End-to-End Memory Network** paper by **Sainbayar Sukhtbaatar, Arthur Szlam, Jason Weston, and Rob Fergus**.
   - Paper link: [End-to-End Memory Networks](https://papers.nips.cc/paper_files/paper/2015/hash/8fb21ee7a2207526da55a679f0332de2-Abstract.html)

---

## Projects

This repository includes a series of practical projects that apply various NLP techniques:

1. **Find the Topic of an Article using LDA**: This project uses **Latent Dirichlet Allocation (LDA)** to discover the main topics of a text article. It involves preprocessing text, applying LDA, and interpreting the results.

2. **Quora Questions Labeling using NMF**: Using **Non-Negative Matrix Factorization (NMF)**, this project classifies Quora questions into various categories. This is an example of text classification with topic modeling.

3. **Word or Next Sentence Prediction**: This project involves training a model to predict the next word or sentence in a given sequence, based on the previous context. This task is often used in NLP applications like auto-completion.

4. **Chatbot using the Babi Dataset**: Building an end-to-end chatbot using **memory networks** for question answering, based on Facebook's **Babi dataset**.

<br>
Note: the last three projects are under development

---

## Online Resources

Throughout this project, I have referenced several online resources to aid my learning. Here are some of the key ones:

- **CountVectorizer vs TF-IDFVectorizer**: A detailed comparison of these two techniques for text vectorization.
  - [Medium article on CountVectorizer vs TF-IDFVectorizer](https://medium.com/@shandeep92/countvectorizer-vs-tfidfvectorizer-cf62d0a54fa4)
- **Gensim Documentation**: Gensim is a popular NLP library, and this page provides a great overview of **topic modeling** using **LDA** and **Word2Vec**.
  - [Gensim Documentation](https://radimrehurek.com/gensim/)

---

## Setup and Installation

To get started with the project, you can clone this repository and set up the environment by installing the required dependencies.

### Prerequisites:

- **Python 3.x**
- **pip** for installing Python packages

### Steps to Set Up:

1. Clone the repository:

   ```bash
   git clone https://github.com/arifhaidari/nlp-exploration.git
   cd nlp-exploration
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv nlp-env
   source nlp-env/bin/activate  # On Windows use `nlp-env\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the code in Jupyter notebooks or Python scripts as needed.

---

## Conclusion

This project provides a broad overview of many important techniques in **Natural Language Processing (NLP)**. From basic string manipulation to advanced deep learning models, the goal is to develop a solid understanding of how NLP works and how to apply these techniques to real-world problems.

As I continue to learn, I will keep adding new projects, techniques, and insights to this repository. This readme will serve as a reference to review what I have learned and track my progress in the field of NLP.
