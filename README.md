# Sentiment Classification Task

This is the repository for the application of Inzva Applied AI 2025 coding question.


## Task

Your task is to create a model to classify the movie comments provided into positive or negative sentiments.

For us to be able to check your solutions, please refer to the **warning section** in [deliverables](#deliverables).

> [!NOTE]
The performance of the model is not the first consideration. Being able to write the training pipeline and explain why a line is written and what does it do is more important.



Here is the **[dataset link](https://ai.stanford.edu/~amaas/data/sentiment)** to start working and **[kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)** to check further solutions.


## Deliverables
In a zip file;

- Python scripts used
- Model file created
- (optional) Visualization to show performance metrics over validation

> [!WARNING]
Although any deep learning framework can be used, please make sure your model file(s) can be loaded in [`load_data`](main.py) and [`predict`](main.py) can be tested in main.py.

> [!CAUTION]
Please exclude the dataset from your .zip file.


## Environment (extra)

You can use the [requirements file](requirements.txt) to create a new environment if you would like to start with a basic setup.

### with python's venv
`pip install virtualenv`
`python -m venv <env_name>`

to activate `source env/bin/activate`

then `pip install -r requirements.txt`

### with conda
`conda create -n <env_name> python=3.12`

to activate `conda activate <env_name>`

then `pip install -r requirements.txt`


