# Sephora Skincare Product Analysis

This project collects information about >2000 skincare products from Sephora. Using this information, a linear regression model was built to predict the average rating for each product. Predicting product popularity can help businesses better allocate resources and capitalize on emerging opprtunities, thus enhancing their competitive positioning in the market. The average prediction generated from the linear regression model is ~4, which is the average rating of all the skincare products. 

Additionally, an interactive Tableau visualization was built for consumers. Consumers can explore their favorite brands and products and gain insight into the average costs of these products.

## File Descriptions

- `code/ScrapeSephora.ipynb`: This Jupyter notebook extracts and saves all skincare product URLs. For each URL, the html file or webpage was saved. From each wepage, product details were extracted and saved into a CSV file. 
  
- `code/CleanSephoraProducts.ipynb`: This Jupyter notebook preprocesses the data for model building. It renames columns, applies string transformations, extracts product size, filters skincare products, generates dummy variables, and creates product connections.

- `code/ProductAnalysis.ipynb`: This Jupyter notebook performs exploratory data analysis using ydata_profiling, creates a network graph of products and their recommended products, builds a linear regression model to predict average ratings of products. 

## Tableau Visualization

Check out the Tableau visualization of the skincare products [here](https://public.tableau.com/views/Sephora_skincare/SephoraSkincare?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link). This visualization provides a comprehensive overview of the skincare products analyzed in this project.


