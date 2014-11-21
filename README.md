#Get data set from
This project is created using data from MovieLens. Download data from [MovieLens](http://grouplens.org/datasets/movielens/)

1. Extract movies.dat and ratings.dat files in the root directory.
2. Create virtual env and intall dependencies
```
mkvirtualenv movierecommender
pip install -r requirements.txt
```
or
```
source movierecommender
activate movierecommender/bin/activate
pip install -r requirements.txt
```
don't do
```
  pip freeze > requirements.txt
```

4. run
```
python movie.py
```
these files will be generated
```
  svd-S
  svd-Ut
  svd-Vt
  svd.ids.cols
  svd.ids.rows
  result.dat
  result.json
```
