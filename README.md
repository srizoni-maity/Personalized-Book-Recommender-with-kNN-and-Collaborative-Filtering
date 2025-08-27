# Book Recommendation System using Machine Learning

A machine learning project that builds a **personalized book recommendation engine** using the **Book-Crossing dataset** from Kaggle. The system applies **collaborative filtering** and the **k-Nearest Neighbors (kNN)** algorithm to recommend books based on user preferences.

---

## 📂 Project Structure
- `Untitled40.ipynb` → Main Jupyter Notebook with full implementation.
- `requirements.txt` → Python dependencies.
- `README.md` → Project documentation.

---

## ⚡ Features
- ✅ Downloads and integrates the **Book-Crossing dataset**.  
- ✅ Cleans and preprocesses books, ratings, and users data.  
- ✅ Builds a **sparse user–item matrix** for scalability.  
- ✅ Implements **k-Nearest Neighbors (kNN)** for recommendations.  
- ✅ Visualizes rating distributions and book popularity.  

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/srizoni-maity/book-recommender.git
cd book-recommender

# Create a virtual environment (recommended):
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


# Install dependencies:
pip install -r requirements.txt

▶️ Usage
Obtain a Kaggle API token (kaggle.json) from Kaggle
Place the token in the notebook when prompted.
Run the notebook Untitled40.ipynb step by step to build and test the recommender system.


📊 Results / Outputs
Book popularity analysis
Rating distribution plots
Top-N recommended books for a given input


📌 Requirements
Python 3.8+
Kaggle API
Libraries listed in requirements.txt


🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.
