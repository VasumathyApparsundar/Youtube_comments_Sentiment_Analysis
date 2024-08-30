# Sentiment Analysis of Tamil YouTube Channels

## Project Overview

This project performs sentiment analysis on comments from three popular Tamil YouTube channels. The goal is to classify comments into Positive, Negative, and Neutral sentiments using Natural Language Processing (NLP) techniques and machine learning models.

## Channels Analyzed

- **Nakkalites**
- **Village Cooking Channel**
- **Madan Gowri**

## Technologies Used

- **Python**: For data processing, sentiment analysis, and modeling.
- **NLTK**: For natural language processing and sentiment analysis.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning, including data vectorization and model training.
- **Google Colab/Jupyter Notebook**: For running and executing the code.

## Data Sources

The data for this project is collected from YouTube comments. The dataset includes comments from the specified Tamil YouTube channels.

## Project Structure

1. **Data Preparation**:
   - Data loading and preprocessing.
   - Handling text data in Tamil and English.
   - Text normalization and cleaning.

2. **Sentiment Analysis**:
   - Sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner).
   - Handling sentiment classification and label encoding.

3. **Data Balancing**:
   - Upsampling minority sentiment classes to balance the dataset.

4. **Model Training**:
   - Vectorization of text data using `CountVectorizer`.
   - Training a Gaussian Naive Bayes model.

5. **Evaluation**:
   - Performance evaluation using Confusion Matrix and Accuracy Score.

## Results

The sentiment analysis results for each channel are as follows:

### Nakkalites
- **Accuracy**: 89.2%
- **Confusion Matrix**:
    ```
    [[268   6  28]
     [  0 263  15]
     [ 11  34 245]]
    ```

### Village Cooking Channel
- **Accuracy**: 100%
- **Confusion Matrix**:
    ```
    [[63  0  0]
     [ 0 72  0]
     [ 0  0 73]]
    ```

### Madan Gowri
- **Accuracy**: 82.5%
- **Confusion Matrix**:
    ```
    [[515  22  86]
     [  0 631   0]
     [182  36 389]]
    ```

## Installation and Setup

To run the code in this repository, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git

2. **Clone the repository**:
   ```bash
   pip install numpy pandas nltk scikit-learn googletrans==4.0.0-rc1 langdetect

3. Download the dataset and place it in the data/ directory (or update the code to reflect the correct path to your dataset).

4. Open the Jupyter Notebook or Python script and run the cells to perform sentiment analysis.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.
