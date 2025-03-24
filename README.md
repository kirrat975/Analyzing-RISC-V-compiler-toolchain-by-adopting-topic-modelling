
# 🚀 Analyzing RISC-V compiler toolchain by adopting topic modelling 

This study explores **GitHub repositories** and **mailing lists** to obtain key insights using **topic modelling** and **data retrieval techniques**. It aims to assist developers in **domains with limited tutorials or documentation**, where GitHub and mailing lists are the **primary sources of knowledge**.  

### 🎯 **Project Focus**  
🔹 **Target Domain:** Compiler development with a focus on **RISC-V architecture**.  
🔹 **Goal:** Identify main topics and discussions to help new and experienced developers navigate complex codebase.  

---

## 🔑 **Key Features**  

✅ **Data Retrieval:** Extracts relevant **commits, patches, and mailing discussions** using the **Whoosh search engine**.  
✅ **Topic Modelling:** Applies different techniques to find hidden topics in **commits and mailing lists**.  
✅ **Evaluation Metrics:** Evaluates topic quality using **Coherence (CV, C_NPMI, U_Mass) and Topic Diversity**.  
✅ **NLP Processing:** Preprocesses text via **tokenization, lemmatization, removal of unnecessary texts and stopwords(English and custom) removal**.  
✅ **Visualization:** Uses **graphs and word clouds** for **intuitive topic interpretation** and Exploratory Data Analysis (EDA) for insights about datasets.  

---

## 🧠 **Topic Modelling Techniques Used**  

🔹 **LDA** (Latent Dirichlet Allocation) – Probabilistic topic modelling  
🔹 **NMF** (Non-Negative Matrix Factorization) – Matrix factorization-based topic extraction  
🔹 **LSA** (Latent Semantic Analysis) – Singular Value Decomposition for topic identification  
🔹 **Top2Vec** – Unsupervised topic discovery using **Doc2Vec** representation  
🔹 **Word2Vec** – Embeddings for **semantic similarity** between words  
🔹 **CTM** (Correlated Topic Modelling) –Gives topics on basis of correlation

---

## 📊 **Evaluation Metrics**  

📈 **Coherence Scores** (CV, C_NPMI, U_Mass) – Measure topic **quality and interpretability**.  
📈 **Topic Diversity** – Ensures a broad range of meaningful topics which are unique in nature.  

---

## 📂 **Data Sources**  

📌 **RISC-V GNU Toolchain GitHub repository** – Extracted using **Pydriller** library, including:  
✔ **Commit messages**  
✔ **Patches**  
✔ **Metadata (authors, timestamps, files changed, etc.)**  

📌 **GCC Mailing Lists** – Collected using **Requests** and **BeautifulSoup** libraries, capturing:  
✔ **Developer conversations  (mails)**  
✔ **Patch submissions**  

---

## 🛠 **How to Use**  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/kirrat975/Analyzing-RISC-V-compiler-toolchain-by-adopting-topic-modelling.git
cd Analyzing-RISC-V-compiler-toolchain-by-adopting-topic-modelling

```

### 2️⃣ **Install Required Dependencies**  
Ensure all required Python libraries are installed:  

```
Pandas  
Numpy  
Matplotlib  
Seaborn  
Gensim  
Wordcloud  
Scikit-learn  
Top2Vec  
Tomotopy  
Whoosh  
OCTIS  
```

### 3️⃣ **Run the Jupyter Notebook**  
Launch Jupyter Notebook and execute the cells to:  

✔ **Extract and preprocess data**  
✔ **Perform topic modelling**  
✔ **Retrieve relevant information using Whoosh**  
✔ **Visualize results**  

---

## 📈 **Expected Outcomes**  

🚀 **Identification of Key topics** in RISC-V **compiler toolchain development**.  
🔎 **Efficient data accessibility** for new developers in the **compiler domain**.  

---
