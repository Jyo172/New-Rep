# New-Rep
Adclicks classification problem:
A leading affiliate network company from Europe wants to leverage machine learning to improve(optimise) their conversion rates and 
eventually their topline. Their network is spread across multiple countries .
Affiliate network is a form of online marketing channel where an intermediary promotes products/services and earns commission based on conversions (click or sign up). 
The benefit companies sees in using such affiliate channels is that, they are able to reach to audience which doesn’t exist in their marketing reach.
The company wants to improve their CPC (cost per click) performance. A future insight about an ad performance will give them enough 
headstart to make changes (if necessary) in theirupcoming CPC campaigns.
The task is to predict the probability of whether an ad will get clicked or not.

The program flow goes as data cleaning, data visualisation, feature engineering and model fitting with prediction.

Observations:Target class is highly imbalance; Features site id and offerid dont contribute to the output much; used mean encoding;
combined various features; MinMaxscaling has improved the ROC AUC score significantly
