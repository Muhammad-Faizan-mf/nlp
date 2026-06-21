# NLP Core Workspace: From Tokenization to Advanced Word Vectors

Welcome to the NLP development repository. This repository serves as a step-by-step structural pipeline for modern Natural Language Processing (NLP). It documents a hands-on progression starting from fundamental text parsing, progressing through traditional statistical feature extraction, and concluding with dense vector architectures (**Gensim**, **spaCy**, and Meta AI's **fastText**).

---

## 📂 Repository Roadmap & Module Directory

The codebase is organized sequentially, tracing the natural evolution of NLP techniques:

### Phase 1: Text Preprocessing & Linguistics Foundations
* **`1_regex`** – Custom tokenization mechanics and text pattern isolation using regular expressions.
* **`2_spacy_vs_nltk`** – Side-by-side performance benchmarking of industrial processing (`spaCy`) against research processing (`NLTK`).
* **`3_tokenization`** – Deep dive into core word/sentence tokenization strategies.
* **`4_spacy_lang_processing_pipeline`** – Inspecting token attributes inside spaCy's native pipeline architecture.
* **`5_stemming_lematization`** – Text normalization using algorithmic stemming and morphological lemmatization.
* **`6_pos`** – Part-of-Speech tagging to extract structural and syntax-level grammar tokens.
* **`7_named_entity_recognition`** – Extracting real-world atomic entities (Locations, Organizations, Dates, Names).
* **`9_ stop_words`** – Filtering low-signal functional noise words to optimize computational overhead.

### Phase 2: Sparse Vector Space Modeling (Traditional ML)
* **`8_bag_of_words`** – Frequency-based binary counts modeling.
* **`10_bag_of_n_grams`** – Preserving spatial context by modeling contiguous token chunks (Bigrams, Trigrams).
* **`11_tf_idf`** – Implementing Term Frequency-Inverse Document Frequency weight scoring to isolate distinct vocabulary significance.

### Phase 3: Dense Word Embeddings & Classification Pipelines
* **`12_spacy_word_vectors`** – Loading pre-trained static embeddings via spaCy.
* **`13_word_vectors_spacy_text_classification`** – Training supervised downstream classifiers directly over structural spaCy vector representations.
* **`14_word_vectors_gensim_overview`** – Deep exploration of distributional semantics utilizing the **Gensim** framework.
* **`15_word_vectors_gensim_text_classification`** – Engineering classification models backed by custom-built Gensim vectors.
* **`16_fasttext_classification`** – High-speed supervised text classification processing leveraging character sub-word models.

---

## 🛠️ Environment Prerequisites & Hardware Setup

Because deep text frameworks like `fasttext` rely heavily on raw compilation layers, modern environments running recent runtimes (like **Python 3.13**) require system hooks and exact package locking to ensure stability.
