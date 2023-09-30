# Predicting-successful-upsells

## Dataset

It was obtained from one of the coffee point. For seven days there was audio recorder and then it was translated to text transcripts. In parallel with that worker of one company listened the audio and checked where it was successful try of upselling.

Before using the text data I check that it contains empty lines in which we don't have a text of dialogue, so I removed such lines. Then I change types of columns to prepare to fitting.

## Results

After the fitting and training the models I achieve such results:
- sklearn.linear\_model.LogisticRegression: $65.88\%$.
- Catboost.CatBoostClassifier: $67.06\%$.
- Keras.Sequential: $62.35\%$.

It represents that after preprocess data you can get more that baseline results,
but simple sequential neuro model isn't better than standart classifiers. And as you
can see the difference between them isn't high and so you can use any of them
as baseline to other improvements.
