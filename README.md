# 📰 Topic Modeling on BBC News Dataset

This project applies **Topic Modeling** using **Latent Dirichlet Allocation (LDA)** to the **BBC News Dataset** in order to discover hidden topics and themes in a collection of news articles. It is part of an NLP internship series focused on applying unsupervised learning techniques to real-world datasets.

## 📌 Project Objectives

- Automatically uncover dominant topics in news articles
- Understand underlying structure in textual data using unsupervised NLP
- Visualize the relationships between topics using interactive tools

## 📂 Dataset

- **BBC News Dataset**: A collection of news articles categorized into business, entertainment, politics, sport, and tech.
- Source: [Kaggle or other dataset repository]

## 🛠️ Tools & Libraries

- **Python**
- **Gensim** – LDA implementation
- **NLTK** – Text preprocessing (tokenization, stopword removal)
- **pyLDAvis** – Interactive topic visualization
- **Pandas, Matplotlib, Seaborn** – Data handling and plotting

## ⚙️ Workflow

1. **Load Data**: Load and explore the BBC News dataset
2. **Preprocessing**:
   - Lowercasing
   - Tokenization
   - Stopword removal
   - Lemmatization
3. **Create Dictionary & Corpus**:
   - Convert text into bag-of-words format
4. **Build LDA Model**:
   - Use `Gensim` to apply LDA
   - Tune number of topics
5. **Evaluate Coherence Score**:
   - Evaluate model performance
6. **Visualize Topics**:
   - Use `pyLDAvis` for interactive visualization

## 📊 Output Example

Each topic is represented as a group of top keywords. For example:

 Topic 1: ['game', 'team', 'win', 'match', 'season']
 Topic 2: ['government', 'minister', 'policy', 'vote', 'election']


## 📈 Results

The model revealed meaningful topics corresponding to real-world categories like sports, politics, technology, and entertainment. This helps in automatic content organization and summarization.

## 📚 Learning Outcomes

- Gained hands-on experience with unsupervised NLP using LDA
- Learned how to prepare and clean textual data
- Understood the importance of hyperparameter tuning (like `num_topics`)
- Practiced interactive topic visualization with `pyLDAvis`

## 🧠 Future Work

- Apply advanced topic modeling (e.g., BERTopic)
- Integrate clustering methods (KMeans, t-SNE) for visual insights
- Test with larger and more diverse datasets

## 🔗 Project Links

- 📁 [Jupyter Notebook (if public)](YOUR_NOTEBOOK_LINK)
- 🔍 [Interactive Visualization Screenshot](YOUR_IMAGE_LINK)

---

**Author**: [Haneen Ebrahim]  
**Internship**: NLP Track @ Elevvo  


