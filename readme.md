What makes a successful web novel?

We scrape the metadata of over 50k web novels from RoyalRoad.com, and we use that metadata to determine the factors that contribute most to success in terms of total views and followers. We train an XGBoost model to predict from metadata (review scores, the number of chapters, tags, etc.) how likely it is that the web novel is among top 5% of all web novels based on the number of followers. Then we use SHAP values to inspect the effect of each feature on the prediction.

See the associated Tableau for more analysis.