
# Spotify and YouTube Data Analysis Project

This project performs exploratory data analysis (EDA) on a dataset containing information from both Spotify and YouTube. The analysis focuses on understanding trends in music and video streaming platforms and provides insights into popularity, user engagement, and content trends.

## Dataset

The dataset contains data from both Spotify and YouTube, including:
- Song and video titles
- Artist or creator information
- Popularity metrics such as views, streams, likes, and shares
- Release date and duration of content
- Genre and tags associated with the content

You can access the dataset from the Kaggle page: [Spotify and YouTube Data Analysis](https://www.kaggle.com/code/aryaupadhyay95/spotify-and-youtube-data-analysis).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/spotify-youtube-eda.git
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

After installing the necessary dependencies, run the analysis script to generate insights and visualizations.

```bash
python analysis.py
```

This script performs the following tasks:
- Loads and cleans the Spotify and YouTube dataset.
- Conducts exploratory data analysis, including:
    - Distribution of content across platforms (Spotify vs YouTube).
    - Popularity trends over time.
    - Analysis of top artists and creators.
    - Correlation between various metrics (e.g., views, likes, streams).
- Generates visualizations for key trends and metrics.

## Project Structure

- `analysis.py`: The main Python script for data analysis and visualization.
- `data/`: Contains the dataset (download from Kaggle and place it here).
- `visualizations/`: Folder where generated plots and figures are saved.
- `requirements.txt`: List of dependencies needed to run the project.

## Results

The analysis revealed the following key insights:
- The most popular artists and creators tend to dominate both Spotify and YouTube, but the metrics for success can vary significantly between platforms.
- Popularity trends show seasonal peaks, particularly around the release of new music and viral videos.
- Strong correlations were found between views and likes on YouTube, while Spotify streams showed a more gradual growth pattern.

## Credits

Dataset provided by [Arya Upadhyay](https://www.kaggle.com/code/aryaupadhyay95/spotify-and-youtube-data-analysis) on Kaggle.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
