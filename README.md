<div align="center">
  <h1>Crime Classification</h1>
</div>

## OBJECTIVE
The objective of this project is to develop robust machine learning models for classifying textual data into categories of 'Sexist' or 'Racist'. Leveraging natural language processing (NLP) techniques and supervised learning algorithms, our objective is to build models that can accurately discern and categorize text-based content, empowering users to detect instances of sexism and racism within textual data.

## IDEA
Given the diverse nature of the provided dataset, which encompassed various cyber crimes, our focus was on the `twitter_sexism_parsed_dataset.csv` and `twitter_racism_parsed_dataset.csv` files. We trained separate LSTM (Long Short-Term Memory) networks on these datasets, performing tokenization and lemmatization as preprocessing steps. After training, we saved the trained models. 

## Implementation
We created `sexism_classifier.ipynb` and `racism_classifier.ipynb` notebooks for training and saving the LSTM models for sexism and racism classification respectively. These notebooks should be run first to save the trained models. Then, the `crime_classification.ipynb` notebook can be executed to load these pretrained models and classify new text data.

## Versions
- TensorFlow version: 2.16.1
- Pandas version: 2.2.1
- NumPy version: 1.23.5
- NLTK version: 3.8.1
- Keras version: 3.0.5

## Model Performance
- `sexism_classifier.ipynb` has attained an accuracy of 0.8572 and a loss of 0.4666.
- `racism_classifier.ipynb` has attained an accuracy of 0.9081 and a loss of 0.3188.

## Output Image
After running `crime_classification.ipynb`, the following output image is obtained:
![Output Image](https://github.com/stackaway/Crime_classification/blob/main/Images/output.png)

## Conclusion
Through the development and implementation of the crime classification system, we have successfully demonstrated the effectiveness of utilizing machine learning techniques for identifying instances of sexism and racism within textual data. The achieved accuracies and model performance metrics underscore the potential of such approaches in addressing and combating cyber crimes involving hate speech and discriminatory content.

*Churnika S Mundas*

  
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/churnika-mundas-64767b246/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/stackaway) 
