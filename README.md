
---

## 📝 Project Overview

This project is divided into two major sections:

### **Section 1 – Agent-Based Models**
1. **Agent-Based Model with Inference (Discrete Evolution Model)**  
   - Simulates how linguistic variants spread in a community.  
   - Implements **Approximate Bayesian Computation (ABC)** for parameter inference.  
   - Includes modeling of **migration** between two locations.  

2. **Social Dynamics Model with Agent-Specific Imbalance**  
   - Extends the model by incorporating **age factors** and **individual linguistic biases**.  __
   - Replaces spline-based imbalance with a **sigmoid function**.  
   - Demonstrates generational replacement as a driver of language change.  

---

### **Section 2 – Neural Networks**
1. **Language Family Prediction using Neural Networks**  
   - Predicts language families from phonological features.  
   - Two architectures implemented:  
     - **Feature-based model** (binary phonological features).  
     - **Embedding-based model** (learned phoneme embeddings).  
   - Dataset: ~97k samples, 173 language families (highly imbalanced).  
   - Framework: **PyTorch**  

2. **Character-Based Word Generation (CBOW)**  
   - Implements a **Continuous Bag of Words (CBOW)** model at the character level.  
   - Trained on ~42k unique English words.  
   - Generates novel character sequences with English-like structure.  

---

## ⚙️ Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
