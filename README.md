# Music Recommendation System

This project is a music recommendation system that leverages machine learning techniques to recommend songs based on user input. The system utilizes datasets of songs with various attributes such as valence, danceability, and energy to provide personalized recommendations.

## Features

- **Data Preprocessing and Feature Engineering:**
  - Cleaned and transformed the dataset to ensure accurate and relevant song recommendations.
- **Clustering and Dimensionality Reduction:**
  - Implemented K-Means clustering and PCA to group similar songs and reduce data dimensions for visualization.
- **Visualization:**
  - Created insightful plots using Plotly and seaborn to illustrate song clusters and relationships.
- **Scalable Recommendation Pipeline:**
  - Developed a robust pipeline using `scikit-learn` and `pandas`, enabling the system to adapt dynamically to new data and user preferences.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/bbiaggi88/music-recommendation-system.git
    cd music-recommendation-system
    ```

2. Create a virtual environment and activate it:
    ```sh
    python3 -m venv env
    source env/bin/activate
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the root directory and add your Spotify API credentials:
    ```env
    SPOTIFY_CLIENT_ID=your_client_id
    SPOTIFY_CLIENT_SECRET=your_client_secret
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook recommendation_system.ipynb
    ```

2. Run the cells in the notebook to execute the music recommendation system.

## Data

The datasets used in this project includes various attributes of songs such as valence, danceability, energy, instrumentalness, liveness, and more.

## Results

- The system provides song recommendations based on user input.
- Visualizations include t-SNE and PCA scatter plots to illustrate song clusters.
- Recommendations are personalized and dynamically adapt to new data.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- [Spotipy](https://spotipy.readthedocs.io/en/2.19.0/)
- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/python/)
- [Seaborn](https://seaborn.pydata.org/)
