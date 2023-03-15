IMDB Movie Rating Prediction
This project is a Python script that predicts the rating of a movie based on its title using linear regression and text analysis. The script scrapes the top-rated movies from IMDB, preprocesses the data by removing missing values, applies text analysis using the TfidfVectorizer, and trains a linear regression model to predict the rating of a movie based on its title.

Prerequisites
Python 3.x
requests
beautifulsoup4
scikit-learn
Installation
Clone the repository or download the script
Install the prerequisites by running pip install -r requirements.txt in your terminal
Usage
Open your terminal and navigate to the project directory
Run the script using python imdb_rating_prediction.py
Enter the title of the movie you want to predict the rating for
The script will output the predicted rating for the movie
Example
yaml
Copy code
$ python imdb_rating_prediction.py
Enter a movie title: The Godfather
Predicted rating for The Godfather : 9.2
Limitations
The model's accuracy heavily depends on the quality of the data used to train it. The model was trained on the top-rated movies from IMDB, so it may not be as accurate for predicting the ratings of movies outside that dataset.
The model only takes into account the movie title and does not consider any other factors that may affect the rating of a movie, such as the cast, plot, or genre.
License
This project is licensed under the MIT License. See the LICENSE file for details.