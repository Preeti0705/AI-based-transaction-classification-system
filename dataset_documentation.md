##  Dataset Description

The model is trained and evaluated using a modified subset of the **Kaggle Daily Transactions Dataset**.  
While the original dataset contains multiple transactional attributes such as `Date`, `Mode`, `Amount`, and `Currency`, this project specifically utilizes only two columns: **Note** and **Category**.

###Link
-https://www.kaggle.com/datasets/prasad22/daily-transactions-dataset
### Columns Used

- **Note**  
  The textual description of each transaction.  
  This acts as the **input feature** for the NLP model.

- **Category**  
  The labeled classification of the transaction.  
  This acts as the **target output** during model training.

### ⚙️ Reason for Using Only These Columns

Other columns were excluded since the primary objective of the project is **text-based transaction classification** rather than financial amount analysis or temporal modeling.

### Dataset Processing

The dataset was:
- Cleaned to remove null and inconsistent values  
- Preprocessed for NLP tasks  
- Aligned with a **custom transaction taxonomy**  

This prepared dataset was used to fine-tune **DistilBERT** for domain-specific financial transaction classification.
