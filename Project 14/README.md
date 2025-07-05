# Sentiment Classification – IMDB Movie Reviews

## Project Overview  
The Film Junky Union, a community for classic movie enthusiasts, is developing an automated system for filtering and categorizing movie reviews. The primary goal is to build and evaluate machine learning models that can accurately classify IMDB movie reviews as positive or negative based on sentiment.

The project utilizes a labeled dataset of movie reviews with polarity information, and the target is to achieve an F1 score of at least **0.85** for negative review detection.

---

## Project Objectives  
✔️ Load and preprocess the IMDB reviews dataset  
✔️ Conduct Exploratory Data Analysis (EDA), including class balance assessment  
✔️ Transform text data for machine learning (vectorization)  
✔️ Train and compare at least three different classification models  
✔️ Test models using provided test data and evaluate performance using F1-score  
✔️ Compose custom reviews and classify them using all trained models  
✔️ Present findings and explain any performance differences between models  

---

## Dataset Description  
The dataset used for this project is sourced from:

*Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. ACL 2011.*

**File:** `imdb_reviews.tsv`  

**Key Columns:**  
- `review` – Text of the movie review  
- `pos` – Target label (`0` = negative, `1` = positive)  
- `ds_part` – Indicates whether the row belongs to the training or test set  

Additional fields are present in the dataset and can be explored for deeper insights.

---

## Project Workflow  
1. **Data Loading & Preprocessing**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering & Vectorization**  
4. **Model Development & Training**  
5. **Model Evaluation with F1-Score**  
6. **Custom Review Testing**  
7. **Conclusions & Findings**  

---

## Evaluation Criteria  
✅ Text data is properly preprocessed and vectorized  
✅ At least three models are trained and tested  
✅ F1-score meets or exceeds 0.85 threshold  
✅ Code cells are structured and executable without errors  
✅ Clear conclusions are presented  

**Reviewer Expectations:**  
✔️ Logical project structure  
✔️ Clean, well-documented code  
✔️ Avoidance of code duplication  
✔️ Meaningful insights from the results  

---

## Notes on BERT Usage  
BERT-based models are computationally intensive and typically require GPU resources. If BERT is utilized, it is applied only to a small sample of the dataset for demonstration purposes.

---

## Author  
**Justin Watts** — Data Science Portfolio  
[LinkedIn](https://www.linkedin.com/in/justin-watts-0234562a7)  
[Email](mailto:wattsjay28@gmail.com)  
