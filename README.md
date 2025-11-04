# Final-Year-Thesis-Project-Demo-

# 🌐 বাংলা Harassment Detection Demo / Bengali Harassment Detection Demo  

> 🧠 *An interactive browser-based demo for real-time detection of Bengali cyberbullying and harassment using concepts from mBERT and Explainable AI.*

---
## 🚀 Overview
This project demonstrates a **simulation** of a Bengali cyberbullying and harassment detection model directly in the browser — no installation, no backend.  
It mimics the decision behavior of transformer-based models such as **mBERT** and **BERT+CNN hybrid architectures**, allowing users to test and visualize results instantly.

🔍 The tool is designed for research presentation, public awareness, and defense demonstration purposes.

---
## ✨ Features
- ⚡ **Instant text analysis** — classify Bengali sentences in real time.  
- 🧩 **Category detection:**  
  - Gender-based harassment  
  - Religion-based harassment  
  - Age-based harassment  
  - Ethnicity-based harassment  
  - Miscellaneous/general abuse  
- 💬 **Confidence bar** — simulates model certainty.  
- 🧠 **Explainable AI concept** — interpretable results.  
- 🎨 **Modern neon-glass UI** — designed for academic demonstration.  
- 🌐 **Bilingual interface (Bengali + English)** for accessibility.

---

## 🧩 Technical Concept
The demo is inspired by the actual research architecture involving:

| Component | Description |
|------------|-------------|
| **Machine Learning Models** | SVM, XGBoost, etc. |
| **Deep Learning Models** | CNN, BiLSTM, GRU, etc. |
| **Transformers** | mBERT, XLM-RoBERTa, etc. |
| **Explainability** | LIME (Local Interpretable Model-agnostic Explanations) |

🧾 **Dataset:** Over **55,000 Bengali social media texts**  
📈 **Best accuracy:** Up to **93%** (BERT embeddings with CNN/ANN hybrid)

---
## 🧭 How to Use
1. Download or clone this repository.  
2. Open **`index.html`** in any modern browser (Chrome, Edge, Firefox).  
3. Type a Bengali sentence (e.g., *“তুমি একদম গাধা”*) and click **“চেক করুন”**.  
4. Observe classification results and confidence visualization.

💡 *No internet or installation required after download — it’s a standalone HTML demo.*

---
## 🌱 Future Work
- 🧩 Integrate the **real mBERT model** using TensorFlow.js or a lightweight backend API.  
- 🧍‍♂️ Develop a **browser extension** or moderation tool for real social media.  
- 🔎 Implement **context-aware detection** and sarcasm understanding.  
- 🌈 Add **token-level heatmaps** (LIME/SHAP) for explainability visualization.  
- 🌍 Deploy as a **public awareness or educational platform** for online safety in Bengali communities.

---
## ⚠️ Limitations & Possible Mistakes
| Type | Description |
|------|--------------|
| **Keyword Dependence** | The demo uses specific words to classify harassment, which can lead to false positives. |
| **Lack of Context** | Neutral sentences containing keywords may be misclassified. |
| **Code-Mixed Text** | Sentences mixing Bengali and English may not be handled accurately. |
| **Transliteration Ambiguity** | The word “হ্যুরেসমেন্ট” may translate incorrectly (e.g., to “hurricane”) in auto-translation tools. |
| **Simplified Logic** | Unlike real mBERT, this demo doesn’t capture semantic meaning — it’s rule-based for visualization. |

Despite these, the demo **effectively demonstrates** the concept of AI-assisted moderation and the importance of interpretability in **low-resource languages**.


---
## 📘 Acknowledgment
This demo is part of an academic research project on **Cyberbullying Detection in Bengali Social Media** using **Machine Learning**, **Deep Learning**, and **Transformer-based** architectures.  
It aims to support research in **AI for social good**, **language inclusivity**, and **digital well-being**.

---
**👩‍💻 Author:** Gazi Jahin  
**🏫 Institution:** International Islamic University Chittagong (IIUC)  
**📅 Year:** 2024 

---

> ⚖️ *This is a conceptual and educational prototype. It should not be used for real-world moderation or decision-making without proper validation and bias testing.*
