

Sentiment Analysis on Movie Reviews 🎬

About the Project

I built this project to explore how deep learning can understand the sentiment behind movie reviews — whether they’re positive or negative. It’s based on the IMDB dataset and uses a combination of **Conv1D** and **LSTM** layers in Keras, along with **GloVe** word embeddings to better understand the meaning of words.

What’s Inside

* 📓 Jupyter Notebook with all steps: preprocessing, model building, training, and testing.
* 📁 Dataset: IMDB reviews in CSV format.
* 🧠 Pre-trained GloVe embeddings (for word meaning).
* 💾 Trained model saved for reuse.
 Tech Stack

* Python, TensorFlow, Keras
* Pandas, NumPy
* Matplotlib, Seaborn, WordCloud
* scikit-learn

 What I Did

* Cleaned and preprocessed the text data
* Visualized common words in reviews using WordClouds
* Loaded GloVe embeddings for deeper word understanding
* Designed a Conv1D + LSTM model
* Evaluated model performance using accuracy and loss

 How to Try It

1. Clone the repo:

   ```
   git clone https://github.com/Nancy-200507/Sentimal_Analysis_Proj.git
   cd Sentimal_Analysis_Proj
   ```
2. Install the required libraries
3. Open the notebook and run the cells step-by-step

Results

The model achieved good accuracy on validation data and shows consistent learning over epochs.




