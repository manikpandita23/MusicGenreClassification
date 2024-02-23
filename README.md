Music Genre Classification and Recommendation System
Overview
This project is a music genre classification and recommendation system that leverages machine learning and audio signal processing techniques. The goal is to classify music genres based on audio features and provide a recommender system to suggest similar songs.

Key Components
1. Data Loading and Exploration
Audio files are loaded from a specified directory using the librosa library.
Waveforms of audio files are displayed to explore their characteristics.
2. Feature Extraction
Audio features, such as Mel-frequency cepstral coefficients (MFCCs) and tempo, are extracted using librosa and python_speech_features.
The dataset is created, containing audio features and corresponding genre labels.
3. Data Visualization
A boxplot is generated to visualize the distribution of BPM (Beats Per Minute) across different music genres.
A detailed distribution view is provided using a violin plot.
4. Data Preprocessing
Feature scaling is applied using Min-Max scaling.
Principal Component Analysis (PCA) is employed for dimensionality reduction.
5. Machine Learning Models
Various machine learning models, including Random Forest Classifier, K Nearest Neighbors, and Support Vector Machine, are trained to classify music genres.
Model performance is evaluated using K-Fold cross-validation.
6. Cosine Similarity and Recommender System
Cosine similarity is calculated between songs based on their audio features.
A recommender system is implemented, suggesting similar songs based on the currently playing song.
How to Use
Clone the Repository:
git clone https://github.com/your-username/music-genre-classification.git
cd music-genre-classification

Install Dependencies:
pip install -r requirements.txt

Run the Jupyter Notebooks:
Execute the Jupyter notebooks in the notebooks directory to explore and run specific components of the project.

Explore Results:
View the generated visualizations and results within the notebooks to understand the classification models' performance and the effectiveness of the recommender system.

Note
Adjustments may be required, especially related to file paths or missing libraries.
Ensure all necessary libraries (librosa, python_speech_features, etc.) are installed before running the code.
