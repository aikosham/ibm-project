# Recommendations With IBM

This repo contains the files required for the IBM project. We analyze the interactions that users have had with articles on IBM Watson Studio platform and make recommendations.

There were 3 sections of the notebook that guided us to fill it out:

1. Exploratory Data Analysis
2. Rank based Recommendations
3. User-user based collaborative filtering

## Results
- If we don't have a rating from the user about the article, their interactions with the article can give a measure of the article's popularity.
- Similar users can be used to provide recommendations to each other. Although we did not explore this in much more detail, I think this is often a significant factor.
- In the dataset given, accuracy saturated after a certain number of latent features were achieved
