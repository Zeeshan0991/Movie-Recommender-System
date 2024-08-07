# Movie Recommender System

This is a web application that recommends the top 5 similar movies based on the searched movie. The recommendations are displayed along with their posters. The application is built using Streamlit and relies on a precomputed similarity matrix to find similar movies.

## Features
- Search for a movie by title.
- Get top 5 movie recommendations based on similarity.
- Display movie posters of the recommended movies.

## Installation

### Prerequisites
- Python 3.7+
- Streamlit
- Pandas
- Requests
- Pickle

### Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/Zeeshan0991/Movie-Recommender-System.git
    cd Movie-Recommender-System
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Place the necessary data files (`movies_dict.pkl` and `similarity.pkl`) in the root directory of the project.

4. Run the application:
    ```sh
    streamlit run app.py
    ```

## Usage

1. Open the application in your web browser.
2. Select a movie from the dropdown menu.
3. Click the "Recommend" button to get the top 5 similar movies along with their posters.

## Data Files
- `movies_dict.pkl`: A pickle file containing a dictionary of movie data.
- `similarity.pkl`: A pickle file containing the precomputed similarity matrix.

## License

This project is licensed under the MIT License - see the (LICENSE.txt) file for details.

# Directory Structure

Movie-Recommender-System/
├── app.py
├── movies_dict.pkl
├── similarity.pkl
├── README.md
├── LICENSE.txt
└── requirements.txt
