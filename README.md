# ibm-recommendations
Recommendations system for articles on the IBM Watson Studio platform - Data Scientist nanodegree project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Libraries used: sys nltk re string numpy pandas pickle sklearn flask json plotly sqlalchemy. Python version: 3.7.12

## Project Motivation<a name="motivation"></a>

In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. This project analyses article and user interaction data to build a recommendation system that personalises the user experience by connecting them with relevant assets. Rank-based and user-based collaborative filtering techniques are used. 

## File Descriptions <a name="files"></a>

+ Recommendations_with_IBM.ipynb: notebook used for ETL and building recommendation systems
+ articles_community.csv: articles dataset containing the text content, description, name, status and article id of each article
+ user-item-interactions.csv: interactions dataset containing the article id, title and email id of each user that has viewed each article

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
The dataset and project design were sourced from Udacity and IBM. Some of the functions used in the code were taken from exercises as part of the Udacity Data Scientist nanodegree 2022.
