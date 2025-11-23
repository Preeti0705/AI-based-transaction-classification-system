# AI Automated Finance Categorization

This project is a **financial transaction categorization system** using AI.  
It automatically classifies transaction descriptions into meaningful expense or income categories.

---

## 🚀 Project Overview

- Uses **DistilBERT**.
- Classifies expense transactions into categories.
- Works **offline** – no internet needed after setup.
- Focuses on **privacy-friendly** local processing.

---

## 📂 Dataset Used

We used the **Daily Transactions Dataset** from Kaggle.

From the full dataset, we only used:
- `Note` – Transaction description  
- `Category` – Transaction category (label)

Why only these two?
- Our goal is **text-based classification**
- Other columns like amount, date, and mode were not needed for this task.

---

## 🧠 How It Works

1. Input: Transaction description (like: *"Paid Swiggy order"*).
2. The text goes into the trained **DistilBERT model**.
3. The model predicts the correct transaction category.
4. User can correct wrong predictions → model can improve later.

---

## 🔑 Key Features

- NLP-based category prediction  
- DistilBERT for fast and efficient performance  
- Custom, editable category structure  
- Explainable predictions (shows why a result was predicted)  
- Feedback loop to improve accuracy over time  
- Works fully offline (no cloud needed)

---

## 🛠️ Tech Stack

- Python  
- DistilBERT (HuggingFace Transformers)  
- PyTorch  
- Pandas  
- Scikit-learn  

---
