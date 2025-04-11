# Analyzing Global Food Wastage - Data Science Portfolio Project
## Project Overview:
This project focuses on using Python to explore and analyze global food wastage, with the goal of answering the following questions:
- Which countries have the highest economic loss per ton of food waste?
- Which countries saw the most significant year-over-year change in total food waste?
- Does high household waste % correlate with certain food categories?

The project code and results are contained in the Jupyter Notebook `global_food_wastage.ipynb`, with a summary of the conclusions below.

## Data:
The data used in this project is spread across two CSV files stored in the datasets directory:
- `global_food_wastage_dataset.csv` contains the data from 2018 to 2024 for food waste from 19 countries all over the world
- `world_populations.csv` contains population data from the 19 countries listed in the former dataset
Credit: `global_food_wastage_dataset.csv` can be obtained from Kaggle using the following link, and `world_populations.csv` is compiled by me using population data from macrotrends.net
- https://www.kaggle.com/datasets/atharvasoundankar/global-food-wastage-dataset-2018-2024
Thanks to the dataset author for releasing this data into the public domain.

## Conclusion:
In summary, this project provides valuable insights into the trends of global food wastage from 2018 to 2024. Here are some key findings from the analysis:
- China, Argentina, and Australia have the greatest economic loss per ton of food waste. 
- USA in 2022 and Italy in 2023 experienced the greatest year-over-year increase in total food waste from their respective previous years, whreas China in 2019 and India in 2021 showed the largest reductions in total food waste
- Bakery items have the strongest correlation (0.65) meaning that in countries with high overall household food waste, bakery items are especially over-wasted.

There are a couple of caveats to these conclusions that we can address in future analyses which include:
- We're looking only at food waste % and tonnage without context like income, or food production levels
- This dataset ignores industry, farm-level, and supply chain losses, ony focusing on household waste
- This dataset doesn’t include reasons for food waste  

## Python Version and Library Dependencies
Python (3.8.10)
numpy==1.22.2
pandas==1.4.1
