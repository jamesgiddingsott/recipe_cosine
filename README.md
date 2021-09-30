# recipe_cosine
Recipe scraper and Menu builder using Cosine Similarity

This Google Colab notebook uses the recipe-scrapers library to grab various recipes from the web.
The instructions from these recipes are then vectorized and a matrix is built using a cosine similarity algorithm to determine
how alike the two recipes are.  This information is then loaded into a dataframe and then visualized in a heatmap.

Additionally, the notebook can also randomize the selection of a weekly menu based on a total similarity score to hopefully create menus 
with a very high culinary diversity.  
