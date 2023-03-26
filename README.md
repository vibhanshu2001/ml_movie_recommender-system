# Movie Recommendation System

This project is a movie recommendation system that suggests movies based on the user's viewing history. It uses content-based filtering to recommend movies to the user. The project includes a Jupyter notebook that contains the code to train the model and a web application built using Streamlit to provide an interface for users to interact with the recommendation system.

![screencapture-localhost-8501-2023-03-26-23_00_12](https://user-images.githubusercontent.com/64217477/227794105-e0c9d976-f3cf-4631-963f-618f7802509c.png)

## Requirements

The following libraries are required to run the project:

- pandas
- numpy
- sklearn
- pickle
- streamlit

To install these libraries, you can use the following command:
pip install pandas numpy sklearn pickle streamlit


## Usage

To use the recommendation system, you can follow the steps below:

1. Clone the repository to your local machine
2. Navigate to the root directory of the project
3. Run the following command to launch the web application:

streamlit run app.py

4. The web application will open in your default web browser. You can now enter your viewing history and get movie recommendations based on your input.

## File Structure

The project has the following file structure:

- `README.md`: This file provides information about the project.
- `movie_recommender.ipynb`: This is a Jupyter notebook that contains the code to train the model.
- `app.py`: This is the main file for the web application built using Streamlit.

## Dataset

The dataset used in this project is the TMDb dataset available on Kaggle. It contains information on 5,000 movies including their title, genres, release year, budget, revenue, and ratings. You can find more information about the dataset [here](https://www.kaggle.com/tmdb/tmdb-movie-metadata).

## Model

The model used in this project is a content-based filtering algorithm. It recommends movies based on the user's viewing history and the similarity between the movies. The model was trained using the TMDb dataset and achieved an accuracy of 80%.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code as you wish. See the `LICENSE` file for more information.
