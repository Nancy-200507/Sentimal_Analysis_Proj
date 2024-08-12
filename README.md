# Sentiment Analysis on Movie Review Data

## Overview
This project aims to perform sentiment analysis on the IMDB movie review dataset. It utilizes deep learning techniques, particularly LSTM and Conv1D layers, to classify movie reviews into positive and negative sentiments. The model is built using Keras and GloVe embeddings for word representations.

## Project Structure
- **Sentiment Analysis of Movie Review using Keras.ipynb**: The main notebook containing code for data preprocessing, model building, training, and evaluation.
- **dataSentimental/IMDB Dataset/IMDB Dataset.csv**: The dataset containing movie reviews.
- **dataSentimental/glove/glove.840B.300d.pkl**: Pre-trained GloVe embeddings used for word representation.
- **trained_model/Sentiment_Analysis/imdb_model.h5**: The saved model after training.

## Libraries Used
- TensorFlow & Keras
- Pandas
- NumPy
- Seaborn
- Matplotlib
- WordCloud
- scikit-learn

## Key Features
1. **Data Preprocessing**: Handling missing values, encoding labels, and data cleaning to remove unwanted characters and contractions.
2. **Data Visualization**: Visualizing the most frequent words in positive and negative reviews using WordCloud.
3. **GloVe Embeddings**: Using pre-trained GloVe embeddings to enhance the model's understanding of word semantics.
4. **Model Architecture**: A combination of Conv1D, LSTM, and Dense layers with dropout for reducing overfitting.
5. **Model Evaluation**: Evaluating model performance using metrics like accuracy and loss.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/rishimule/Sentiment-Analysis-of-Movie-Reviews.git
    ```
2. Navigate to the project directory:
    ```bash
    cd sentiment-analysis-movie-reviews
    ```
3. Install the required libraries:

4. Run the Jupyter notebook `Sentiment Analysis of Movie Review using Keras.ipynb` to preprocess data, train the model, and evaluate its performance.

## Results
The model achieved a training accuracy of X% and a validation accuracy of Y%. The loss and accuracy plots indicate the model's learning curve over the epochs.

## Authors
- Hashir Khan
- Rishi Mule

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
