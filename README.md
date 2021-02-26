# Recommendation Engines

## Description

**recommendation_engines** works with MovieTweetings data to provide user with movie recommendations. We explore three types of recommendation systems: knowledge based, collaborative filtering and content based:

1. Knowledge based

	- Use knowledge about items that meet user specifications to recommend items.

2. Collaborative filtering

	- Based on using the collaboration of user-item interactions.

3. Content based

	- Use information about items to find item similarities. Often similarities are related to item descriptions or purpose.

## Dependencies

disaster_response_pipelines requires:

- NumPy
- pandas
- progressbar

## Folder Descriptions

1. [data](https://github.com/joshua-furtado/recommendation_engines/tree/main/data)

	- Contains the raw and cleaned data.

## File Descriptions

2. [wrangling.ipynb](https://github.com/joshua-furtado/recommendation_engines/blob/main/wrangling.ipynb)

	- Jupyter notebook for data wrangling.
	- Extracts data from movies.dat and ratings.dat in the [data](https://github.com/joshua-furtado/recommendation_engines/tree/main/data) folder, transforms the data, and loads it into movies_clean.csv and reviews_clean.csv (stored in the [data](https://github.com/joshua-furtado/recommendation_engines/tree/main/data) folder as well).

3. [knowledge_based.ipynb](https://github.com/joshua-furtado/recommendation_engines/blob/main/knowledge_based.ipynb)

	- Jupyter notebook for knowledge based movie recommendations.

4. [collaborative_filtering.ipynb](https://github.com/joshua-furtado/recommendation_engines/blob/main/collaborative_filtering.ipynb)

	- Jupyter notebook for movie recommendations using collaborative filtering.

5. [content_based.ipynb](https://github.com/joshua-furtado/recommendation_engines/blob/main/content_based.ipynb)

	- Jupyter notebook for content based movie recommendations.

## Authors

**Joshua Furtado**