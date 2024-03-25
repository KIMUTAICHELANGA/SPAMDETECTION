## SMS Spam Classification Project README

### Project Overview:
This project aims to classify SMS messages as either spam or ham (non-spam) using machine learning techniques. The project involves several steps including data preparation, exploratory data analysis (EDA), text preprocessing, feature extraction using TF-IDF, and model building with various classification algorithms.

### Steps Involved:

1. **Data Preparation:** 
   - The SMS dataset is loaded from a CSV file.
   - Unnecessary columns are dropped from the dataset.
   - A new column 'Count' is added to represent the length of each SMS message.
   
2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics are computed to understand the distribution of message lengths for spam and ham messages.
   - Word clouds are generated to visualize the most common words in spam and ham messages.
   
3. **Text Preprocessing:**
   - Text processing techniques such as removing stopwords, punctuation, and applying stemming are performed.
   - The 'label' column is converted to a numerical variable.
   
4. **Feature Extraction using TF-IDF:**
   - TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is applied to convert text data into numerical features.
   - The dataset is split into training and testing sets.
   
5. **Model Building:**
   - Multinomial Naive Bayes, K-Nearest Neighbors (KNN), and Decision Tree classifiers are implemented.
   - Model performance metrics such as accuracy, precision, recall, and F1-score are evaluated.
   - Receiver Operating Characteristic (ROC) curves are plotted for model comparison.

### Results:

- Multinomial Naive Bayes achieved an accuracy of 95.09%.
- K-Nearest Neighbors (KNN) classifier achieved an accuracy of 90.43%.
- Decision Tree classifier achieved an accuracy of 95.39%.

### Conclusion:
Based on the results, the Decision Tree classifier performed the best in terms of accuracy. However, further fine-tuning and optimization of models could potentially improve performance. Additionally, incorporating more advanced techniques such as ensemble methods or neural networks could be explored for better classification results.
