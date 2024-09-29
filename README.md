# Resume-Screening-ML
This project is an NLP-based Resume Classification System. The goal of this project is to automatically classify resumes into predefined job categories (e.g., Data Science, Java Developer, etc.) using text preprocessing, TF-IDF for feature extraction, and machine learning algorithms such as KNeighborsClassifier and OneVsRestClassifier.
# Key Components
## Data Preprocessing:
Tokenization, lemmatization, and stopwords removal using NLTK.
This cleans the resume text and makes it ready for further processing.
## TF-IDF Vectorization:
The resume text is converted into numerical features using TF-IDF.
This helps in capturing the importance of words in each resume relative to others.
## Model Building:
KNeighborsClassifier is used for classification into job categories.
OneVsRestClassifier handles multiple categories by converting the multi-class problem into multiple binary classification problems.
## Evaluation:
The model is evaluated using metrics like accuracy, precision, recall, and F1-score.
## Results
The model achieves the following performance metrics on the test set:

Accuracy: 98%
Precision: 0.98
Recall: 0.97
F1-Score: 0.97
## Future Improvements
Use deep learning models such as BERT to improve classification accuracy.
Implement Named Entity Recognition (NER) to extract specific information like skills or qualifications from resumes.
Deploy the model as a web application using Flask or Streamlit for real-time resume classification.
