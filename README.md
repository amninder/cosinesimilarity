#MovieRecommender
This project is created using data from MovieLens. Download data from [MovieLens](http://grouplens.org/datasets/movielens/).

You can obtain result at [movie.narota.com](http://movie.narota.com). This is still in begining stage and it will take a little longer to render 9372 movies with recommendation.

1. Extract movies.dat and ratings.dat files in the root directory.
2. Create virtual env and intall dependencies
```
mkvirtualenv movierecommender
pip install -r requirements.txt
```
or
```
virtualenv movierecommender
source movierecommender/bin/activate
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

```python
def foo():
  print "This is a sample sentence."
```
