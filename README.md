# **Do AI Models Learn Human Biases?**  
### *A Romanian Language Case Study Comparing Biases Reflected by WEAT and CA-WEAT Tests*

---

## 📖 Project Overview  
This project investigates how AI language models inherit and reflect **cultural and linguistic biases**, focusing on **Romanian**. Using **Word Embedding Association Test (WEAT)** and its culturally adapted variant **CA-WEAT**, we compare biases in monolingual (FastText) and multilingual (mBERT, XLM-R) embeddings.  

Prior research suggests that **monolingual models retain stronger biases**, while multilingual models may attenuate them. Our goal is to analyze whether this trend holds for Romanian.

---

## 🔬 Key Research Questions
- Do **monolingual embeddings** exhibit stronger biases than **multilingual ones**?  
- Does **multilinguality** reduce bias, and if so, to what extent?  
- How do **cultural biases** manifest in Romanian embeddings, and can **CA-WEAT** better capture them compared to WEAT?

---

## 🛠 Methodology  
- **WEAT**: Measures bias in word embeddings by evaluating associations between **predefined word lists** (e.g., "flowers" vs. "insects" with "pleasant" vs. "unpleasant").  
- **CA-WEAT**: A culturally adapted version where word lists are customized to reflect **Romanian-specific linguistic and cultural context**.  

### **Models Tested**  
- **FastText** (monolingual, static embeddings)  
- **mBERT** (multilingual, contextual embeddings)  
- **XLM-R** (advanced multilingual embeddings)  

### **Statistical Methods**
- **Cosine Similarity**: Measures how closely words relate in the embedding space.  
- **Association Score**: Quantifies how strongly a word aligns with an attribute.  
- **Effect Size \(d\)** (Cohen’s \(d\)): Measures bias strength across embeddings.  

---

## 📊 Results Summary  
- **FastText** exhibited the **strongest biases**, confirming that monolingual embeddings **retain cultural biases**.  
- **mBERT** showed bias **reduction**, but biases were still **detectable**.  
- **XLM-R** displayed the **weakest biases**, supporting the idea that **cross-lingual learning attenuates bias**.  
- **CA-WEAT revealed cultural nuances** that were not captured by the standard WEAT test.  

---

## 🚀 Insights for Future Work 
- **Expand CA-WEAT** testing to other underrepresented languages.  
- **Refine multilingual models** to preserve cultural identity while mitigating unwanted biases.  
- **Investigate sentence-level bias** in contextual embeddings.  

