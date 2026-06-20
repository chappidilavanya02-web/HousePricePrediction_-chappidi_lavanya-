# House Price Prediction 

Hey there! This repository contains my project submission for Week 1 of the Data Science Internship. The goal this week was to dig into a housing dataset, figure out what actually drives property values, and build a machine learning model to predict prices.

## What's inside?
- analysis.ipynb — My main Jupyter Notebook where all the magic happens (data cleaning, modeling, and visualizations).
- Housing.csv — The raw dataset with all the house details used for training.
- summary.docx — A quick, one-page summary report translating the technical findings into plain business terms.
- charts/ — A folder where I exported the main visual plots (the price distribution histogram, correlation heatmap, and the actual vs. predicted scatter plot).

## Quick Takeaways & What I Learned
- What matters most: Property size, how many bathrooms a house has, and whether it has air conditioning are by far the biggest drivers behind higher house prices. 
- The winning model: Simple Linear Regression took the crown this week with an R² score of 0.6529 (explaining about 65.3% of the price changes). 
- Overfitting struggles: I tried a Random Forest Regressor too, but since our dataset is pretty small (436 rows for training), it overfit a bit and scored a lower 0.6119. Sometimes simpler models just work better!
- A little surprise: I expected having a basement or being right on a main road to matter a lot more, but they actually had a surprisingly low impact compared to basic layout features.

## Running it locally
If you want to run the notebook yourself, just clone the repo, make sure you have the usual suspects installed (pandas, matplotlib, and seaborn), open up analysis.ipynb in Jupyter or Colab, and run the cells from top to bottom.
