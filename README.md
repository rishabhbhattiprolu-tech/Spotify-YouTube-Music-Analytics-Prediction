# 🎵 Spotify–YouTube Music Analytics & Prediction

This project analyzes how songs perform across Spotify and YouTube, combining audio features, metadata, and engagement metrics to understand what drives popularity. Using machine-learning models, it predicts Spotify stream counts and explores cross-platform trends in modern music consumption.

📊 Dataset

The dataset includes song-level information such as:
- Artist, track, album, and album type
- Spotify audio features (danceability, energy, loudness, tempo, etc.)
- Spotify stream counts
- YouTube views, likes, comments, and official video indicators
These features allow for a combined analysis of listener behavior and viewer engagement across both platforms.

🚀 Workflow

Data Preprocessing – Cleaning missing values, normalizing numerical columns, and removing duplicates.
Exploratory Data Analysis (EDA) – Visualizing feature distributions, correlations, and top-performing artists.
Model Training – Using XGBoost, Random Forest, and Linear Regression to predict Spotify streams.
Evaluation – Measuring RMSE, MAE, and R² across models.
Feature Importance – Identifying which audio traits and YouTube metrics most influence popularity.

✅ Results

Model R²: ~87% (replace with notebook value)
RMSE: ~557854.9
YouTube engagement significantly improves prediction accuracy
Audio features like loudness, energy, and danceability show strong correlations

🛠️ Installation

Clone the repository and install requirements:
git clone https://github.com/yourusername/spotify-youtube-analysis.git
cd spotify-youtube-analysis
pip install -r requirements.txt
Run the notebook:
jupyter notebook SpotifyYoutube.ipynb

🔮 Future Work

- Add genre-specific analysis
- Deploy interactive Streamlit dashboard
- Expand dataset with weekly chart data
- Perform deeper hyperparameter tuning
