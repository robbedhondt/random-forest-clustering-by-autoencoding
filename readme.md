# Random Forest Clustering by Autoencoding
This repository hosts the code used in the publication "Random Forest Clustering by Autoencoding" by Robbe D'hondt, Felipe Kenji Nakano, and Celine Vens.

To set up your environment:
```
python3.11 -m pip install -r requirements.txt
```

Download the data from https://github.com/gagolews/clustering-data-v1/releases/tag/v1.1.0 .

To run the benchmark experiments for both methods:
```
mkdir benchmark
mkdir benchmark/pred
touch benchmark/timing.txt
python3.11 benchmark.py
```

To post-process the results into a dataframe:
```
python3.11 results.py
```
