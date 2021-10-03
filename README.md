# recipe_cosine
Recipe scraper and menu builder using Cosine Similarity to create culinary diversity.

This Google Colab notebook uses the recipe-scrapers library to grab various recipes from the web.
The instructions from these recipes are then vectorized and a matrix is built using a cosine similarity algorithm to determine
how alike the two recipes are.  This information is then loaded into a dataframe and then visualized in a heatmap.

Additionally, the notebook can also randomize the selection of a weekly menu based on a total similarity score to hopefully create menus 
with a very high culinary diversity.  

Click the .ipynb file above to view the notebook on GitHub.  Additionally, one can for the notebook for personal use or use the "Open in Colab" icon at the top of the notebook to run and edit their own version right in the browser.
