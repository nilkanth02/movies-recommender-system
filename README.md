

# Movie Recommender System

## Overview

Welcome to the **Movie Recommender System**! This project provides personalized movie recommendations based on user input. Using movie data and similarity metrics, the system suggests movies similar to the one you choose. It also fetches and displays movie posters from TMDb (The Movie Database) API for an enhanced user experience.

## Features

- **Movie Recommendations**: Get a curated list of movies similar to your selection.
- **Movie Posters**: View posters for recommended movies.
- **Interactive Interface**: Built with Streamlit for a seamless and interactive user experience.

## Installation

To get started with this project, follow these steps:

### Prerequisites

- Python 3.7 or higher
- Git

### Clone the Repository

```bash
git clone https://github.com/nilkanth02/movie-recommender-system.git
cd movie-recommender-system
```

### Set Up a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Usage

1. **Prepare Data**: Ensure you have the required data files (`movies_dict.pkl` and `similarity.pkl`). Place these files in the root directory of the project.

2. **Run the Application**:

```bash
streamlit run app.py
```

3. **Interact with the Web App**:
   - Open your web browser and go to [http://localhost:8501](http://localhost:8501).
   - Select a movie from the dropdown list.
   - Click the "Show Recommendation" button to view recommended movies

## Data Files

- `movies_dict.pkl`: Contains movie titles and IDs.
- `similarity.pkl`: Contains the similarity matrix used for recommendations.

## API Key

The project uses the TMDb API to fetch movie posters. You'll need a valid TMDb API key. Replace `YOUR_API_KEY` in the `fetch_poster` function with your actual API key.

## Contributing

We welcome contributions! Feel free to fork the repository and submit pull requests. If you have suggestions or improvements, let us know.



## Contact

For any questions or feedback, you can reach out to:

- **Nilkanth D. Ahire** - [nilkanth8747@gmail.com](mailto:nilkanth8747@gmail.com)
- **GitHub Profile** - [nilkanth02](https://github.com/nilkanth02)

Happy recommending!


