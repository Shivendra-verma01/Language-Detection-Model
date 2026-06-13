# Language Detection Model using Machine Learning and NLP

# Project Overview

This project is a Language Detection Model built using Machine Learning and Natural Language Processing (NLP). 
The model identifies the language of a given text input and predicts the corresponding language.

# Dataset

* Dataset contains 10,337 text samples.
* 17 different languages are included:

  * English
  * French
  * Spanish
  * Portuguese
  * Italian
  * Russian
  * Swedish
  * Malayalam
  * Dutch
  * Arabic
  * Turkish
  * German
  * Tamil
  * Danish
  * Kannada
  * Greek
  * Hindi

# Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Natural Language Processing (NLP)

# Machine Learning Algorithm

* Multinomial Naive Bayes ( Navie Bayes Algorithm )
  
# Project Workflow

1. Import required libraries.
2. Load the language dataset.
3. Perform data analysis and validation.
4. Convert text data into numerical features using CountVectorizer.
5. Split data into training and testing sets.
6. Train the model using Multinomial Naive Bayes.
7. Evaluate model performance.
8. Predict the language of user-entered text.

# Model Performance

* Accuracy: 97.77%

# Example Predictions

Input:
Hello, how are you?

Output:
English

Input:
नमस्ते आप कैसे हैं

Output:
Hindi

Input:
ನಮಸ್ಕಾರ ನೀವು ಹೇಗಿದ್ದೀರಿ

Output:
Kannada

# Future Improvements

* Add more languages.
* Deploy the model as a web application using Flask.
* Improve accuracy using advanced NLP techniques.

 Author

Shivendra Verma
Aspiring Python Developer and Data Science Enthusiast
