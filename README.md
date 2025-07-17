<img width="1258" height="70" alt="image" src="https://github.com/user-attachments/assets/fba9dcd2-5e52-4578-ac62-1aa6a0373ca1" />
#📚 E-Commerce Book Recommendation System

This project is a personalized book recommendation system designed for e-commerce platforms. It uses collaborative filtering techniques to suggest books to users based on their past interactions and preferences.

---

## 🚀 Project Overview

In large-scale digital bookstores, users often struggle to discover books that match their interests. This system addresses that challenge by analyzing user-book rating patterns and recommending similar books using a K-Nearest Neighbors (KNN) model with cosine similarity.

Built with a modular pipeline and deployed via an interactive **Streamlit** interface, the system ensures fast and relevant book recommendations.

---

## 🧠 Features

- 📊 **Collaborative Filtering using KNN**
- 🔍 **Real-Time Book Recommendations**
- 🧩 Modular ML pipeline (Data Ingestion → Validation → Transformation → Training → Recommendation)
- 🖼️ Book cover image integration
- ⚙️ Config-driven architecture using YAML
- 🧠 Pre-trained model and serialized data using Pickle
- 💻 Streamlit UI for easy interaction

---

## 🧰 Tech Stack

| Category         | Tools/Libraries                               |
|------------------|------------------------------------------------|
| Programming      | Python 3.7+                                    |
| Libraries        | `pandas`, `numpy`, `scikit-learn`, `PyYAML`    |
| Web Framework    | `Streamlit`                                    |
| Serialization    | `pickle`                                       |
| Configuration    | YAML                                           |
| Data Structure   | `scipy.sparse.csr_matrix`                      |
| Data Source      | [Kaggle Book Dataset](https://www.kaggle.com/datasets/ra4u12/bookrecommendation)

---

## 📂 Project Structure

```
├── app.py                        # Streamlit app entry point
├── research.ipynb               # Model development notebook
├── template.py                  # Recommendation function
├── configuration.py             # Configuration manager
├── components/                  # Data pipeline modules
│   ├── data_ingestion.py
│   ├── data_validation.py
│   ├── data_transformation.py
│   ├── model_trainer.py
├── artifacts/                   # Trained models and serialized objects
├── config/                      # YAML configuration file
├── utils/                       # Utility functions
├── logs/                        # Logging
├── README.md                    # Project documentation
```

---

## 📈 How It Works

1. **Data Ingestion**: Downloads and extracts book dataset from a configured URL.
2. **Data Validation**: Filters users and books based on rating thresholds.
3. **Data Transformation**: Constructs a pivot matrix and converts it to a sparse matrix.
4. **Model Training**: Trains a KNN model with cosine similarity.
5. **Book Recommendation**: Finds and displays top 5 similar books to the one selected.

---

## 🖥️ Streamlit Interface

Launch the app with:
```bash
streamlit run app.py
```

Features:
- Select a book from dropdown
- Click "Show Recommendation"
- View top 5 related books with cover images

---

## 🔮 Future Enhancements

- Integrate content-based filtering using NLP
- Deploy on Heroku / Hugging Face Spaces
- Use deep learning-based recommenders (Autoencoders, Transformers)
- Store user sessions & feedback
- Add multilingual book support

---

## 📚 References

- [Kaggle Book Dataset](https://www.kaggle.com/datasets/ra4u12/bookrecommendation)
- [scikit-learn KNN](https://scikit-learn.org/stable/modules/neighbors.html)
- [Streamlit Docs](https://docs.streamlit.io)
- [PyYAML](https://pyyaml.org)
- [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)

---

## 🔗 GitHub Repository

🔗 https://github.com/mahaprasadsahoo12/E-Commerce-Book-Recommendation-System


---

## 🙌 Author

**Mahaprasad Sahoo**  
MCA | Python & ML Enthusiast  
Email: mahaprasadsahoo11@gmail.com  
LinkedIn: www.linkedin.com/in/mahaprasad-sahoo-48b82720a/
