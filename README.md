🎵 Music Recommendation System (ML + Streamlit + Spotify API)

This project is a Machine Learning–based Music Recommender System that suggests similar songs using lyrics analysis.

The web interface is built using Streamlit, and album covers are fetched using the Spotify API.

🔥 Features

Song recommendation based on TF-IDF + Cosine Similarity

Interactive Streamlit interface

Spotify album cover integration

Hugging Face–hosted model files

Lightweight GitHub repository

🧠 ML Techniques Used

Text preprocessing (tokenization, stemming, cleaning)

TF-IDF Vectorization

Cosine Similarity

Lyrics-based recommendation

🚀 Run Locally
pip install -r requirements.txt
streamlit run app.py

📦 Project Structure
├── app.py                # Streamlit web app
├── requirements.txt      # Python dependencies
├── README.md             # Documentation
└── .gitignore            # Prevents large files being uploaded

📁 Large Files

Large files such as:

similarity (190MB)

df

spotify_millsongdata.csv

are stored separately on Hugging Face Model Hub and downloaded dynamically in app.py.
