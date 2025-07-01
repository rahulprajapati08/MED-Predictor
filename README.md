# 💊 Medicine Recommendation System

This project is a **content-based filtering system** that recommends medicines based on user-reported symptoms. It uses **TF-IDF vectorization** and **cosine similarity** to match symptoms with relevant medicines from a curated dataset.

---

## 🧠 Project Overview

- 🧾 **Objective**: Suggest appropriate medicines based on user-input symptoms
- 🔍 **Approach**: NLP + content-based filtering (no ML training required)
- 🧰 **Tech Stack**: Python, Pandas, Scikit-learn (TF-IDF), Streamlit (optional for UI)
- 📁 **Dataset**: Contains medicines with associated symptoms and usage descriptions

---

## ⚙️ How It Works

1. **Preprocessing**: Text cleaning and normalization of symptom data
2. **TF-IDF Vectorization**: Transform symptom descriptions into numerical vectors
3. **Cosine Similarity**: Compare user-input symptoms against dataset entries
4. **Top-N Recommendations**: Return most relevant medicines sorted by similarity

---

## 🧪 Sample Input & Output

**User Input**:  
> `"fever, body ache, chills"`

**Top Recommendations**:
- Paracetamol — Commonly used for fever and mild pain
- Ibuprofen — Pain reliever and anti-inflammatory
- Dolo 650 — Effective for body pain and high fever

---

## 🔮 Future Enhancements
 - Add spell correction and fuzzy matching for symptoms

 - Incorporate severity and dosage recommendations

 - Integrate with a chatbot or voice assistant

 - Add multilingual support (e.g., Hindi, regional languages)

