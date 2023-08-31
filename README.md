# Empirical_Investigation_of_TMER

The Code is referenced from paper "[Temporal Meta-path Guided Explainable Recommendation](https://arxiv.org/pdf/2101.01433.pdf)".

There are partial changes to the original files.

The differently named folders represent code for different datasets using the TMER algorithm.

## Requirements
python==3.6.12 <br>  networkx==2.5 <br> numpy==1.15.0 <br> pandas==1.0.1 <br> pytorch==1.0.0 <br> pytorch-nlp==0.5.0
<br>gensim==3.8.3


## Data Preparation

The original data can be found in the [amazon data website](https://nijianmo.github.io/amazon/index.html). 
For one type of market, we need two datasets: "metadata" and "ratings only".

## The oder to run the code files:
All of the code files to be run in the following experimental section are using ".ipynb" files, so do not use a ''.py'' file with the same name to run them.

The Python files not mentioned by name in the following are composed of equations, do not to be run.

Considering the 

1.process data 

`data_process.ipynb`

2.learn the user and item representations

`data/path/embed_nodes.ipynb`

3.learn the item-item path representations

`data/path/user_history/item_item_representation.ipynb`

4.learn the user-item path representations

`data/user_item_representation.ipynb`

5.generate user-item and item-item meta-path instances and learn their representations

`data/path/generate_paths.py`<br>
`data/path/user_history/meta_path_instances_representation.ipynb`

6.sequence item-item paths for each user

`data/path/user_history/user_history.ipynb`

7.run the recommendation

`run.ipynb`


