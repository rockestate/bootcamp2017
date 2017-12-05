# bootcamp2017

Baby name recommender website

[https://namesilike.com](https://namesilike.com)

[https://en.wikipedia.org/wiki/Recommender_system](https://en.wikipedia.org/wiki/Recommender_system)

[Baby names dataset](https://s3-eu-west-1.amazonaws.com/rockestate-public/bootcamp/digitiser_dataset.csv)

**Questions**:

- Which names are seen a lot?
- Which names are clicked a lot?
- Which names are clicked a lot per view?

[Recommendation engine notebook](https://github.com/rockestate/bootcamp2017/blob/master/notebooks/recommandation-engine.ipynb)

# Popularity-based recommender

[Popularity dataset](https://s3-eu-west-1.amazonaws.com/rockestate-public/bootcamp/popularity.csv)

**Question**: How often do people click on the most popular name (2016 popularity)?

# Content-based recommender

[Features](https://s3-eu-west-1.amazonaws.com/rockestate-public/bootcamp/features.csv)

**Task**: 
- Merge features and feedback
- Pick a user, and set up a cross-validation loop of the questions
- For each fold, build a random forest model of feedback given the features on the train set and evaluate *correctness* on the test set.
