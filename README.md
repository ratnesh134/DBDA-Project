# Sensitive Document Classification in Banking Sector
This project leverages Natural Language Processing (NLP) and Machine Learning to identify and classify sensitive documents in the banking sector, enhancing document security and compliance. 
By employing the Random Forest algorithm, we achieved an approximate accuracy of 75% in distinguishing sensitive documents from non-sensitive ones. This solution aids in ensuring that sensitive data remains protected, contributing to improved compliance and security measures.

# Overview
In industries like banking, it's essential to classify and protect sensitive documents containing confidential information. This project addresses this need by:

--Identifying documents with sensitive content specific to the banking sector.

--Classifying documents as either sensitive or non-sensitive based on their content.

--Enhancing security and compliance efforts through machine learning-driven document management.

# Features
Sensitive Content Detection: Automatically detects and classifies sensitive content in documents.

Random Forest Classifier: Employs a Random Forest model to categorize documents based on training data.

Data Security and Compliance: Enhances organizational security by managing document sensitivity.


Results
Accuracy: 75%

Precision, Recall, F1 Score: See detailed metrics in the ipynb file.

## Technologies
Python

scikit-learn (for machine learning algorithms)

NLTK/Spacy (for natural language processing)

Pandas and NumPy (for data manipulation)

# Future Enhancements

Enhanced Feature Engineering: Incorporate more advanced NLP features such as TF-IDF, word embeddings, or domain-specific keywords.

Improved Model: Test transformer-based models like BERT for more nuanced text classification.

Ensemble Methods: Explore combining the Random Forest model with other classifiers to potentially improve performance.
