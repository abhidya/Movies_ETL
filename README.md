# Movies ETL 

### Resources Utilized to Complete Analysis
* **Data Sources:** 
[wikipedia-movies.json](https://github.com/cmmgw/Movies_ETL/blob/main/Resources/wikipedia-movies.json), 
[CSV files](https://www.kaggle.com/rounakbanik/the-movies-dataset/download) from [Kaggle.com](https://www.kaggle.com)


* **Languages:** Python, SQL
* **Applications:** PostgreSQL
* **Tools:** Pandas, Jupyter Notebook

### How to inspect

Open the notebooks in order from extraction/cleaning through database loading:

1. `ETL_clean_wiki_movies.ipynb`
2. `ETL_clean_kaggle_data.ipynb`
3. `ETL_function_test.ipynb`
4. `ETL_create_database.ipynb`

The database-loading notebook expects local PostgreSQL credentials and the
MovieLens/Kaggle data files under `Resources/`. Keep credentials out of the
notebooks before committing changes.
