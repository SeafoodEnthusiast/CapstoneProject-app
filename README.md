# CapstoneProject-app

# Capstone Project: Classification and Recommendation of World Tourism Cities

# Project Title
**World City Travel Budget Classification and Destination Recommendations Based on Traveler Preferences**

# Project Overview
This project aims to explore data on world tourist cities based on attributes such as climate, cultural aspects, nature, cuisine, and others, in order to produce:

1. **Budget level classification model** of tourist cities (Budget / Mid-range / Luxury).
2. **Destination recommendation system** based on user preferences (such as culture, adventure, nightlife).
3. **City description clustering** using LLM (Large Language Model) embedding.
4. **Exploration of LLM prompts** to suggest destinations naturally and interactively.

This approach combines machine learning techniques and generative AI to provide real insights and solutions for tourists and tourism industry players.

# Raw Dataset Link
The dataset used is from:
[Worldwide Travel Cities Dataset (Ratings and Climate)](https://www.kaggle.com/datasets/aadhavvignesh/travel-destinations-dataset)

# Insight & Findings

- Tourist cities with **high scores on the aspects of `culture`, `urban`, and `wellness`** tend to fall into the **Luxury** category.
- Tourists with high **nature and seclusion** preferences are more suitable to visit cities with lower or medium budget levels.
- The classification model (Random Forest) is able to predict city-level budgets with fairly good accuracy, supported by important feature analysis.
- Clustering based on LLM embeddings shows the existence of semantic groupings of cities, such as:
- Historical cultural cities
- Tropical & beach cities
- Nature and adventure cities
- Modern urban cities

# AI Support Explanation

This project uses AI in three main forms:

1. **Machine Learning (Random Forest Classifier)** 
To predict the budget of a tourist city based on numeric features such as culture, adventure, nature, nightlife, etc.

2. **Large Language Model (LLM - IBM Granite via Replicate)** 
To answer prompts related to tourist destination suggestions and explore insights from city descriptions.

3. **LLM Embedding + Clustering** 
Using `distiluse-base-multilingual` from Sentence Transformers to convert city descriptions into numeric vectors, then clustering (KMeans) and visualization (PCA) are performed.



