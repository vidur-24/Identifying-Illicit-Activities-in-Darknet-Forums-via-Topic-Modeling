# Dark Web Topic Modeling using LDA

## Overview
This minor project focuses on analyzing **Dark Web textual data** using **Latent Dirichlet Allocation (LDA)** to uncover hidden thematic patterns. The project aims to support academic research in **cybersecurity, threat intelligence, and digital forensics** by identifying dominant discussion topics present in dark-web forums and marketplaces.

---

## Objectives
- Preprocess and clean unstructured dark-web text data  
- Extract meaningful features from textual content  
- Apply LDA for topic discovery  
- Analyze themes related to cybercrime, extremism, and illicit markets  

---

## Methodology

### 1. Data Preprocessing
- Removal of URLs, symbols, and stopwords  
- Tokenization and lemmatization  
- Handling missing values and duplicates  

### 2. Feature Engineering
- Bag of Words (BoW)  
- TF-IDF Vectorization  

### 3. Topic Modeling
- Latent Dirichlet Allocation (LDA)  
- Topic optimization using coherence score  

### 4. Analysis
- Identification of top keywords per topic  
- Topic distribution analysis across documents  

---

## Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - NumPy  
  - pandas  
  - scikit-learn  
  - Gensim  
  - NLTK / spaCy  
  - Matplotlib / Seaborn  

---

## Project Structure
```text
dark-web-topic-modeling/
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   ├── data_preprocessing.ipynb
│   └── lda_topic_modeling.ipynb
├── src/
│   ├── preprocessing.py
│   ├── vectorization.py
│   └── lda_model.py
├── results/
│   └── extracted_topics.txt
├── requirements.txt
└── README.md
```


---

## Installation
```bash
git clone https://github.com/vidur-05/Identifying-Illicit-Activities-in-Darknet-Forums-via-Topic-Modeling.git
cd dark-web-topic-modeling
pip install -r requirements.txt
```

## Usage
```bash
python src/preprocessing.py
python src/lda_model.py
```

---

## Results
- Successfully extracted latent topics from dark-web text data
- Topics correspond to cybercrime, illicit trade, extremist discussions, and underground markets
- Results are interpretable and consistent with existing dark-web research

---

## Ethical Considerations
- This project is strictly for **academic and research purposes**
- No real-time crawling or interaction with active dark-web services
- All datasets used are anonymized or publicly available for research

---

## References
- Blei, D. M. et al., *Latent Dirichlet Allocation*
- Abbasi et al. (2008)
- Scanlon & Gerber (2014)
- Semantic-LDA (2024)
