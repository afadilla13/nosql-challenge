# Eat Safe, Love Food Ratings Analysis

Welcome to the Eat Safe, Love food ratings analysis repository! Our aim is to help the **Eat Safe, Love** magazine team make informed decisions for their articles and reviews by analyzing UK Food Standards Agency ratings data to identify prime restaurant locations.

## Setup and Database

In the `NoSQL_setup_starter.ipynb` notebook:

- Import data from `establishments.json` to the `uk_food` database's `establishments` collection.
- Ensure proper setup, showcase a document using `pprint`, and prepare the collection.

## Database Updates

In the same notebook:

- Introduce and add "Penang Flavours" restaurant.
- Retrieve and use BusinessTypeID for "Restaurant/Cafe/Canteen".
- Remove unwanted establishments in the Dover Local Authority.
- Adjust data types for accuracy.

## Exploratory Analysis

Moving to `NoSQL_analysis_starter.ipynb`:

- Answer key queries by **Eat Safe, Love** with `count_documents`, `pprint`, and Pandas DataFrames.
- Cover:
  - Establishments with hygiene score 20.
  - London establishments with RatingValue >= 4 (using `$regex`).
  - Top 5 RatingValue '5' establishments, sorted by hygiene and proximity.
  - Hygiene score 0 establishments per Local Authority (aggregation used).
- The "Resources" folder contains `establishments.json`.

Stay tuned for insightful recommendations guiding **Eat Safe, Love** towards captivating articles and spot-on reviews. Enjoy the culinary journey! 🍴🔍
