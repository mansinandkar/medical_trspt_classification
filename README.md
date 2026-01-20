# Medical Transcripts Classification using Sequential Forward Selection (SFS)

---

## Project Overview
Healthcare systems generate large volumes of unstructured clinical text in the form of medical transcriptions. 
This project focuses on building a machine learning–based pipeline to classify medical transcription texts into their respective medical specialties using Natural Language Processing (NLP) techniques.

The project emphasizes feature selection using **Sequential Forward Selection (SFS)** to reduce dimensionality while improving classification accuracy, particularly for small and imbalanced datasets.

---

## Dataset
- **Source:** Kaggle (Medical Transcriptions Dataset, scraped from mtsamples.com)
- **Type:** Unstructured clinical text
- **Attributes:**
  - Medical transcription text
  - Medical specialty label
  - Sample name and keywords

The dataset contains transcriptions across multiple medical specialties. Due to imbalance and sparsity, preprocessing and class filtering were required before modeling.

---

## Objectives
The primary objectives of this project are:

- Classify medical transcription texts into appropriate medical specialties
- Reduce feature dimensionality while maintaining high classification accuracy
- Evaluate the impact of feature selection on model performance
- Compare multiple machine learning models on clinical text data
- Analyze challenges associated with multiclass medical text classification

---

## Methodology Overview
1. Data cleaning and filtering  
2. Text preprocessing using NLP techniques  
3. Feature extraction using TF-IDF  
4. Feature selection using Sequential Forward Selection (SFS)  
5. Class balancing using undersampling  
6. Model training and evaluation  

---

## Key Highlights
- Built an end-to-end NLP and machine learning pipeline for clinical text classification
- Applied Sequential Forward Selection to identify optimal textual features
- Achieved:
  - **99% accuracy** for binary classification (Surgery vs Consultation & History)
  - **75% accuracy** for three-class classification due to vocabulary overlap
- Demonstrated limitations of traditional ML models for multiclass medical text problems

---

## Tools and Technologies
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - NLTK
  - Scikit-learn
  - Imbalanced-learn
- **Techniques:**
  - TF-IDF Vectorization
  - Sequential Forward Selection (SFS)
  - Random Undersampling
- **Models:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - Gradient Boosting
  - Categorical Boosting

---

## Results Summary
- Binary classification performed exceptionally well due to distinct terminology
- Multiclass performance declined due to overlapping clinical language
- Feature selection played a critical role in balancing accuracy and overfitting

---

## Contributors
- **Mansi Nandkar**
- **Veer Sanghavi**
- **Tejaswini Kulkarni**
- **Bennet Meneze**

