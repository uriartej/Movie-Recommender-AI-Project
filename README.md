# Movie-Recommender
Silly little AI movie recommender

SET UP
1. Open a terminal 
2. python -m venv env
3. .\env\Scripts\activate
4. Once activated, you can install Flask and other required packages within this environment.
pip install pandas
pip install scikit-learn
pip install fuzzywuzzy
pip install python-Levenshtein
pip install Flask
set FLASK_APP=movieRecommender.py
set FLASK_ENV=development

HOW TO RUN CODE (if you're not already in virtual environment)
$env:FLASK_APP = "movieRecommender.py"
When you want to start up the server for testing 
flask run

        On Linux

 export FLASK_APP=movieRecommender.py
 export FLASK_ENV=development
 flask run