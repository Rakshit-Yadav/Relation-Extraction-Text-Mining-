# Relation-Extraction-Text-Mining

### The paper in the repository is written based on our analysis, research and academia reading. The relevant python notebooks along with their files are hosted in a google drive folder (Link: https://drive.google.com/drive/folders/1m9Mt0UaCbV-WgJtwifmeAvBiQ69PtgPk?usp=sharing).


Below are provided clear instructions as to how the user can access and run the relevant notebooks.


#### Approach 1: CNN - Bi-LSTM Model (Run in Jupyter Notebook environment)

##### Files:
- **Notebooks**:
  - `CNN-Bi-LSTM-Model_Training.ipynb`: Contains the training pipeline for the CNN-Bi-LSTM model.
  - `Inference_Mode_CNN-Bi-LSTM_Model.ipynb`: Used for model inference with the trained CNN-Bi-LSTM model.

- **Component Files**
  - `text_lstm_model.pth`: The trained CNN-Bi-LSTM model file.
  - `inference_components.pth`: Necessary components for inference, including preprocessing configurations.
  - `embedding_matrix.pth`: The trained embedding matrix passed in the model.
  - `glove.6b.100d.txt`: The GloVe embeddings used for training.

##### Instructions:
1. Download the model and component files from the "Approach - 1 (CNN - Bi-LSTM Model)" folder on Google Drive.
2. Place all of these files in the same directory.
3. GloVe embeddings are downloaded directly within the notebooks. This process might take 10-17 minutes depending on your internet connection. Further details are provided in the `Inference_mode_TextLSTM_model.ipynb` notebook.
4. Ensure the Jupyter notebook environment is set up correctly to execute the notebooks.
5. Run any of the two notebooks (Detailed instructions can be found directly in the notebook files).



#### Approach 2: SVM (Run in Google Colab environment)

##### Files:
- **Notebooks**:
  - `SVM_Model_Training.ipynb`: Contains the training pipeline for the SVM model.
  - `Inference_Mode_SVM_Model.ipynb`: Used for model inference with the trained SVM model.

- **Component Files**
  - `cache.pkl`: Contains precomputed values to speed up model inference.
  - `common_words.pkl`: A list containing common English words used during preprocessing.
  - `en-80k.txt`: A text file containing 80,000 English words, used for spell checking.
  - `svm_model.pkl`: The serialized version of the trained SVM model ready for inference.
  - `sym_spell.pkl`: This contains a pre-built dictionary for fast spell checking.
  - `tfidf_vectorizer`: The serialized TF-IDF vectorizer used for inference.
  - `wordnet_lemmas.pkl`: A list containing Wordnet words, used during preprocessing.


### Instructions:
1. Download the notebooks and component files from the "Approach - 2 (SVM)" folder on Google Drive.
2. Place all downloaded files in the same directory.
3. Upload the files in google colab individually or in a folder, ensuring nothing is left out.
4. Run any of the two notebooks (Detailed instructions can be found directly in the notebook files).

