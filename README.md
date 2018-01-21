# Feature-Engineering
Deep Feature Synthesis,  Feature Stacking, Gradient Boosting Regressor, k-fold Cross Validation
1) Using Deep Feature Synthesis to automatically generate rich features from relational database. 
2) Starting with simple features, incrementally improve the feature definitions and examine the corresponding accuray of the
model by Gradient Boosting Regressor
3) Complete feature stacking. Including more robust features can be done by extracting related features (i.e. instances) from a parent entity, 
then adding additional columns to create the entity features matrix. For example, in this case study, we may want to predict trip 
durations taken over weekend, within a set of destinations and apply an aggregate function such as “mean( )” to the column of trips 
duration. By stacking information, we exploit features relationships in deeper levels (or multi-table dataset). Hence, improving 
the model accuracy in theory.
4) Apply k-fold Cross Validation
