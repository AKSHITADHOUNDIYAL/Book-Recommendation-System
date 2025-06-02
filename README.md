# 📚 Book Recommender System

Welcome to the **Book Recommender System** – a smart Streamlit app that helps you find your next great read! Built with 💡 machine learning and 🚀 Streamlit, this app brings together multiple recommendation strategies to suggest books you'll love.

> **🔗 [Download the Dataset & Pretrained Models Here](https://drive.google.com/drive/folders/10sHgCsrVpMkTLjiUDnu3ao5xyEwAMj9r?usp=sharing)**

---

## ✨ Features

🔹 **Simple Recommender**
→ Recommends top books based on overall popularity and average ratings.

🔹 **Content-Based Filtering**
→ Recommends books similar to a selected book by analyzing content features like title and authors.

🔹 **Content-Based Filtering+**
→ Enhanced version that filters out poorly-rated books for more refined recommendations.

🔹 **Collaborative Filtering (SVD)**
→ Uses user-item interaction data to predict and recommend books you'll likely enjoy, powered by a pretrained **Singular Value Decomposition (SVD)** model.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/AKSHITADHOUNDIYAL/Book-Recommendation-System.git
cd book_recommender
```

### 2️⃣ Set Up Virtual Environment (Recommended)

```bash
python3 -m venv venv
source venv/bin/activate  # On Linux/macOS
# venv\Scripts\activate   # On Windows
```

### 3️⃣ Install the Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit App

```bash
streamlit run main.py
```

---

## 📦 Data & Model Access

To keep the repository light, large files like datasets and pretrained models are hosted externally.
📁 Download everything you need from this shared Google Drive folder:
👉 **[Access Data & Models](https://drive.google.com/drive/folders/10sHgCsrVpMkTLjiUDnu3ao5xyEwAMj9r?usp=sharing)**

After downloading, place the data and model files in the appropriate directories as used in the codebase.

---

## 💡 Tech Stack

* Python 🐍
* Pandas & NumPy 📊
* Scikit-learn 🤖
* Surprise (for Collaborative Filtering) 🎭
* Streamlit 🌐
* Google Drive (for data sharing) ☁️

---

## 🎯 Future Improvements

* Add user login & personal reading history
* Integrate with Goodreads/Google Books API
* Deploy on cloud (e.g., Streamlit Community Cloud or Heroku)

---


