# Survey Data Clustering

## Karinderya Survey Dataset

This dataset contains survey data collected from local **karinderya** (small eateries) to analyze ingredient preferences, cooking habits, and kitchen operations.

### Features:
The dataset includes the following categorical features:

- **main_ingredients** – Primary ingredients used in dishes.
- **vegetables** – Types of vegetables commonly included.
- **seasoning** – Preferred seasonings and spices. This excludes most common seasonings
- **important_ingredients** – Essential ingredients listed by the respondents.
- **purchase_frequency** – How often ingredients are purchased.
- **purchase_location** – Where ingredients are sourced from (e.g., markets, supermarkets).
- **ingredient_priority** – Ranking of the importance of their decision when buying ingredient.
- **kitchen_appliances** – Appliances commonly used in food preparation. This only questions uncommon kitchen appliances. 
- **menu_change_frequency** – How often the menu is updated. 
- **daily_dish_selection** – Number of dishes they serve daily.
- **prep_time** – Average preparation time for dishes.
- **cook_time** – Average cooking time.
- **total_time** – Average total time.
- **ingredients_per_dish** – The number of ingredients used per dish.

### Purpose:
This dataset is intended for **clustering analysis** to identify patterns in ingredient selection, cooking processes, and menu planning in small eateries or karinderyas. Moreover, it was used to filter the Common Filipino Ingredients Dataset

#### How to Use:
1. Use the clustering.ipynb
2. import libraries and insert the raw dataset 'karinderya_data.csv'
3. Process each feature in the dataset to check frequency

#### How to Export to PDF:
1. Make sure you have MikTex (download online), nbconvert (pip), and pandoc (choco install pandoc)
1. python -m nbconvert --to pdf --no-input <notebook.ipynb>

