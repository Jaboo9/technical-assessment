# Technical Assessment

This assessment is based on the [Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality) hosted by the UCI Machine Learning Repository.

Note: All aspects of your analysis must be *repeatable* (must be done *in code*!).

## Task 1: Preparation

1. Download the data.
2. Consolidate the red and white wine data.

Submit the following:

- A script so that we can *reproduce* your work.

## Task 2: Regression

1. Perform an exploratory analysis.
2. On the basis of the exploratory analysis form three hypotheses about what factors are most influential to wine quality.
3. Build a model which allows you to assess your hypotheses. In addition, consider the following:

	- Which features are the most important? Why?
	- Interpret the effect of these important features.

4. Rigorously quantify the performance of this model.
5. Construct a parsimonious model.
6. Rigorously quantify the performance of this model.
7. Use one of the models to predict quality for the following wines:

```
                    Wine 1  Wine 2
		    ======  ======
colour                 red   white
fixed acidity          8.3     6.9
volatile acidity       0.5     0.3
citric acid            0.3     0.3
residual sugar         2.5     6.4
chlorides              0.1     0.0
free sulfur dioxide   15.9    35.3
total sulfur dioxide  46.5   138.4
density                1.0     1.0
pH                     3.3     3.2
sulphates              0.7     0.5
alcohol               10.4    10.5
```

Submit the following:

- A script so that we can *reproduce* your work.
- A document detailing:

    - exploratory analysis
    - three hypotheses
    - description of first model (and why it was chosen)
    - most important features in first model
    - effect of most important features
    - assessment of performance (and why you chose a particular metric)
    - description of second model (and why it was chosen)
    - assessment of performance
    - predictions of quality

## Task 3: Classification

1. Perform an exploratory analysis.
2. On the basis of the exploratory analysis form three hypotheses about what factors are most influential for classifying wine colour.
3. Build a model which allows you to assess your hypotheses. In addition, consider the following:

    - Cater for any imbalances between classes.
	- Which features are the most important? Why?
	- Interpret the effect of these important features.

4. Rigorously quantify the performance of this model.
5. Build a more powerful model.
6. Rigorously quantify the performance of this model.
7. Classify the following wines:

```
                    Wine 3  Wine 4
		    ======  ======
fixed acidity          7.1     6.3
volatile acidity       0.4     0.2
citric acid            0.1     0.3
residual sugar         1.9     1.7
chlorides              0.1     0.0
free sulfur dioxide    7.0    23.0
total sulfur dioxide  22.0   108.0
density                1.0     1.0
pH                     3.2     3.1
sulphates              0.6     0.4
alcohol                9.5     9.5
```

Submit the following:

- A script so that we can *reproduce* your work.
- A document detailing:

    - exploratory analysis
    - three hypotheses
    - description of first model (and why it was chosen)
    - any measures for dealing with class imbalance
    - most important features in first model
    - effect of most important features
    - assessment of performance (and why you chose a particular metric)
    - description of second model (and why it was chosen)
    - assessment of performance
    - predictions
