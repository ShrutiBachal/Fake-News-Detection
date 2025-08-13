# 📰 Fake News Detection
This project focuses on detecting fake news articles using Natural Language Processing (NLP) and Machine Learning techniques. It uses labeled datasets of real and fake news to train a classification model that can predict whether a given news article is genuine or fabricated.

📂 Dataset

The project uses two CSV files:

<li>True.csv — Contains legitimate news articles.

<li>Fake.csv — Contains fabricated news articles.

Both datasets were combined into a single DataFrame with a label column:

1 → Real News

0 → Fake News

⚙️ Technologies Used

<li>Python

<li>Pandas, NumPy — Data manipulation

<li>Scikit-learn — Model building & evaluation

<li>Natural Language Processing (NLP)

<li>TfidfVectorizer — Text feature extraction

<li>Logistic Regression — Classification model

🛠️ Methodology

1. Data Loading & Labeling
   
      Load True.csv and Fake.csv, assign labels, and combine into a single dataset.

3. Data Preprocessing

      Text cleaning (removing punctuation, stopwords, and special characters)

      Converting text to lowercase

4. Feature Extraction

      Used TfidfVectorizer to convert text into numerical features.

5. Model Training

      Split the dataset into training and testing sets using train_test_split.

      Trained a Logistic Regression classifier.

6. Model Evaluation

      Evaluated using accuracy, precision, recall, and F1-score.

      Achieved 100% accuracy on the test dataset.

📊 Results
| Metric    | Class 0 (Fake) | Class 1 (Real) | Accuracy |
| --------- | -------------- | -------------- | -------- |
| Precision | 1.00           | 1.00           | **1.00** |
| Recall    | 1.00           | 1.00           | **1.00** |
| F1-score  | 1.00           | 1.00           | **1.00** |

🚀 How to Run

1. Clone the repository.

2. Install required packages:
   
       pip install pandas numpy scikit-learn
   
3. Run the Jupyter Notebook:
   
       jupyter notebook Fake_news_detection.ipynb


