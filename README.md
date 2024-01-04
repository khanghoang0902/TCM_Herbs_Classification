# TCM_Herbs_Classification
<!-- ABOUT THE PROJECT -->
## About The Project

Traditional Chinese Medicine (TCM) has long relied on herbal prescriptions for treating various health conditions based on patient symptoms. This study presents a novel approach to automate the classification of TCM herb prescriptions by leveraging patient symptoms. The dataset encompasses records from over 800 patients, containing information about their symptoms, diagnoses, and prescribed herbal treatments. To accomplish this, the text data underwent comprehensive preprocessing steps, including tokenization and Word2Vec-based embedding generation tailored to TCM specifics. Features were then selected and categorized for each herb to serve as input for the classification models. Random Forest (RF) and Naive Bayes (NB) models were evaluated using metrics such as accuracy and F1-score to gauge their performance. The results demonstrate promising accuracy and F1-scores across different herbs, showcasing the potential for automated classification of TCM prescriptions. Additionally, the study compares binary features with contextual word embeddings, highlighting the advantage of leveraging context-rich embeddings for improved classification accuracy. These findings underscore the potential of utilizing machine learning models to assist in TCM prescription generation based on patient symptoms.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Follow the instructions below:

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. Upload Code -> TCM.ipynp to Google Colab 
2. Open TCM.ipynp in Google Colab
3. Upload Dataset -> medical_cases.csv to Files
4. Go to Runtime, select Run all to execute the model

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MODEL PERFORMANCE -->
## Model Performance 
![image](https://github.com/ngochoawindy/TCM_Herbs_Classification/assets/61321182/7664f0b6-12d9-4ccb-bfed-b9bd29acfa5e)
![image](https://github.com/ngochoawindy/TCM_Herbs_Classification/assets/61321182/5633b101-ad0a-4dc8-bb1a-71c00bded812)

### Model performance details

In comparing the performance of word embedding and binary features for predicting herbal components, word embedding consistently outshines binary features across multiple metrics. The results indicate higher accuracy and F1-scores for most herbal components when employing word embedding. This suggests that the word embedding approach captures more nuanced relationships and context, leading to improved predictive capabilities. Overall, the efficiency of word embedding is evident, emphasizing its effectiveness in enhancing the accuracy and overall performance of the model in the context of herbal component prediction.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

