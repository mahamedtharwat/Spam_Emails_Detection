# Spam Emails Detection 📈 :
## 1. Introduction : 
This Project demonstrates the process of building a spam email detection system. The primary objective is to classify emails as either spam or non-spam (ham) based on their content. This is achieved using machine learning techniques on textual data.
# ![1__igArwmR7Pj_Mu_KUGD1SQ](https://github.com/user-attachments/assets/a37f172f-bf10-4e93-889e-221d024fc0b8)
## 2. Dataset :
 - Source: A dataset containing labeled email messages.
 * Key Features:
   *  text: The content of the email.
   *  label: Categorical labels (spam or ham).
   *  label_num: Numeric representation of the labels (1 for spam, 0 for ham).
 *  Size: 5,171 records with 4 columns.
 * 	Data Preparation:
    * 	Removed newline characters within the email content.
    * 	Verified that there are no missing values.
    * 	Checked for and handled duplicate entries.
## 3. Data Preprocessing :
 - Text Normalization:
   * Converted text to lowercase.
   * Removed punctuation and special characters.
   * Tokenized text and removed stopwords using NLTK.
   * Applied stemming using PorterStemmer to reduce words to their root forms. 
## 4. Feature Engineering :
 - Vectorization:
   * Used CountVectorizer to convert text data into a bag-of-words representation.
   * Generated a sparse matrix of word counts for use in machine learning models.
## 5. Model Training
 - Algorithm: Random Forest Classifier (RFR).
   *	Data Split: 
	    *  80% for training, 20% for testing.
   *	Hyperparameters: Default settings were used unless specified otherwise. 

