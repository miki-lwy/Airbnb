# Airbnb

This project aims at analyzing the reviews of travellers from all over the world using semantic analyzer - Sentiment Analysis and thus, providing a rating accordingly. The reason for not using the review_scores_rating in the listings.csv.gz file is that there are many property listings with the same ratings in which we couldn't tell which property is better. Python widgets are used for creating a form to filter condition(s). Together with the sentiment scores, it helps the users to make the best decision for finding the most suitable place to stay during their trips.

# Installation
```
Install jupyter notebook (please see https://jupyter.org/install for the details)
```

# Required libraries
- Airbnb's Data Analysis.ipynb
```
pip install pandas
pip install numpy
pip install langdetect
pip install vaderSentiment
pip install ast
pip install ipywidgets
```

# Optional libraries 
- Semantic Analysis - Testing.ipynb
```
pip install nltk
pip install textblob
```

# Required dataset
Since the dataset is too big to be uploaded to the Github, you can download it in the website - http://insideairbnb.com/get-the-data.html

```
1) listings.csv.gz -- Detailed Listings data for New York City
2) calendar.csv.gz -- Detailed Calendar Data for listings in New York City
3) reviews.csv.gz -- Detailed Review Data for listings in New York City
4) listings.csv -- Summary information and metrics for listings in New York City (good for visualisations)
5) reviews.csv -- Summary Review data and Listing ID (to facilitate time based analytics and visualisations linked to a listing)
6) neighbourhoods.csv -- Neighbourhood list for geo filter. Sourced from city or open source GIS files
```

# Limitation of this project
- Semantic Analysis - Testing.ipynb file, 
Since the review.csv file contains more than a million rows, it exceeds the google translate limit (5000 characters per day). It will take more than 1000 days to complete the non-English review's translation assuming each review contains about 50 characters. The project duration is 21 days. So, non-English reviews are excluded in the sentiment analysis.

