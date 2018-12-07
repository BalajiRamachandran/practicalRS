# practicalRS

## DATASETS TO DOWNLOAD AND EXTRACT IN dataset/

- [dataset 1](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip
)
- [dataset 2](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Amazon_Instant_Video_5.json.gz)

## SLIDES OF COURSES:

- [Intro to recommenders](http://www-connex.lip6.fr/~dias/RS-intro.pdf)
- [Recent Advances & Deep Learning Architectures](http://www-connex.lip6.fr/~dias/RS-adv.pdf)

## Instructions to get started (ON LINUX)

- Clone repository: `git clone git@github.com:cedias/practicalNLP.git`
- move in directory: `cd practicalNLP`
- download data: `cd dataset`then`chmod +x download.sh` and finally `./download.sh`
- start notebook: `cd ..` if you're still in the  `.../dataset` dir and `jupyter notebook`

## Instructions to get started (ON Windows)

- Clone or Download Repository
- Extract download file
- (Manually) download files listed in "dataset/source" file:

  - [dataset 1](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip
)
   - [dataset 2](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Amazon_Instant_Video_5.json.gz)
```
http://files.grouplens.org/datasets/movielens/ml-latest-small.zip
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Amazon_Instant_Video_5.json.gz
```

- Extract them if needed
- start notebook somehow

##  Install package directly within jupyter notebooks:

```python
import sys
!{sys.executable} -m pip install [--user] package
```
