# Titanic Survival

To most, "Titanic" may evoke imagery of a grand ship, a newspaper headline,
or maybe the iconic picture of Leo & Kate on the bow of the ship. To data
scientists, "Titanic" often reminds us of our first dataset, a *real* dataset,
requiring vast amounts of cleaning, preprocessing, transformation, and
hyperparameter tuning.

Nevertheless, the Titanic dataset is a great place to start with data science
projects. It is a great place to start, covering a wide variety of machine
learning requirements.

## Getting Started

First, clone the repository in a location you'd like:

```Shell
git clone https://github.com/msburns24/Titanic.git
cd Titanic
```

To run this project, you'll need just a few standard tools:

- **Pandas, NumPy** - Data reading, processing, and analysis
- **Matplotlib, Seaborn** - Data visualization
- **Scikit-Learn** - Machine learning models, cross-validation, and training

These can all be installed through `pip`:

```Shell
pip install -r requirements.txt
```

## Results

Several models were tested here to compare performance. Below, you can see the
accuracy that each model performed:

| Model                  | Accuracy |
|:-----------------------|---------:|
| Ada Boost              |   83.80% |
| Logistic Regression    |   83.24% |
| Random Forest          |   82.68% |
| Gradient-Boosted Trees |   82.68% |
| Decision Tree          |   82.68% |
| SVC                    |   80.45% |
| kNN                    |   80.45% |
| Gaussian Naive-Bayes   |   78.21% |
