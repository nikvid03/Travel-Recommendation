# 🧭 Travel Recommendation System

## 📌 Overview
This project implements a **content-based recommendation system** that suggests travel destinations based on the user's interest. Using natural language processing (NLP) and cosine similarity, the system finds places with similar descriptions.

---

## 💼 Features
- Load and clean travel destination dataset
- Vectorize destination descriptions using TF-IDF
- Compute similarity scores using cosine similarity
- Recommend similar destinations based on user input
- Interactive recommendation interface via user prompt

---

## 📁 Project Structure
travel-recommendation-system : 
├── Expanded_Destinations.csv          # Dataset with destination descriptions
├── Travel Recommendation System.ipynb # Main notebook with code
├── README.md                          # Project documentation
├── requirements.txt                   # List of required Python packages (optional)



---

## 📊 Dataset
- **File:** `Expanded_Destinations.csv`
- Contains travel destinations and their associated descriptive text.

---

## ⚙️ Technologies Used
- Python
- Pandas
- Scikit-learn
- NLTK (optional, for text cleaning)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/travel-recommendation-system.git
   cd travel-recommendation-system

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
- Open Travel Recommendation System.ipynb in Jupyter Notebook or VS Code.
- Run all cells and enter a destination when prompted.
