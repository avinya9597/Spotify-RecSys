# spotify-recsys

# Spotify Recommendations Project

## Overview

We aim to develop a recommendation system that effectively balances the delicate interplay between exploration and exploitation for Spotify users. In addressing the diverse preferences of users, our system will consider various dimensions:

1. **Artist Recommendations:**
   - Users seek top recommendations (top k) for specific artists they enjoy.

2. **Time-of-Day Preferences: In-progress**
   - Users desire top k recommendations tailored to the time of day. For instance, recommending upbeat songs in the morning and soothing tunes before bedtime.

3. **Entire Listen History: In-progress**
   - Users want top k recommendations based on their entire listening history, reflecting a comprehensive understanding of their music preferences.

In navigating these user scenarios, Spotify faces a perennial dilemma: whether to introduce users to new songs to bolster the popularity of emerging artists or to recommend familiar songs aligned with users' historical preferences.

The crux of the matter lies in the tradeoff between these two choices. Recommending new songs holds the potential to elevate the popularity of emerging content, but it carries the risk of user dissatisfaction, potentially leading to a switch to another song or even app disengagement. On the other hand, suggesting songs aligned with users' historical preferences ensures a safer user experience, benefiting both the user and the app.

Our recommendation system aims to strike the right balance in this exploration-exploitation tradeoff. It seeks to enhance user satisfaction by intelligently recommending a mix of familiar favorites and promising new content, ensuring an engaging and personalized music experience for Spotify users.

## Getting Started

### Prerequisites

- Python 3.x
- Install dependencies using `pip install -r requirements.txt`

### Project Setup

1. Clone the repository: `git clone https://github.com/your-username/spotify-recommendations.git`
2. Navigate to the project directory: `cd spotify-recommendations`

### Data

1. Obtain the Spotify dataset (e.g., from [Spotify API](https://developer.spotify.com/documentation/web-api/))
2. Place the dataset in the `data/raw_data/` directory with the name `spotify_dataset.csv`

### Data Processing

1. Run data preparation script: `python src/data_preparation.py`
2. Run feature engineering script: `python src/feature_engineering.py`

### Model Training

1. Run the model training script: `python src/model_training.py`

### Recommendation

1. Utilize the recommendation script: `python src/recommendation.py`

## Project Structure

- **data/:** Contains raw and processed data.
- **src/:** Source code for data preparation, feature engineering, model training, and recommendations.
- **models/:** Stores trained models.
- **notebooks/:** Contains .ipynb files for data extraction, data exploration, preparation

## Description

Collaborative Filtering: Utilizes user-item interactions to find similar users or items.
Content-Based Filtering: Uses user and item features to make recommendations.

## Contributors
- Sreevani Patil (@srpa2129@colorado.edu)

## License
This project is licensed under the MIT License - see the LICENSE file for details.




