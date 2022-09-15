# Comparisons of clustering algorithms (in astronomy contexts and elsewhere)

I've done various bits of work on clustering algorithms over the years ([including a paper comparing them applied to Gaia](https://ui.adsabs.harvard.edu/abs/2021A%26A...646A.104H/abstract)). This repo is intended as a central location collecting different things I've done in one place.

## Cloning this repo

Note that this repo uses **submodules**. If you want to clone all this repo _and_ its constituent submodules to your local machine in one command, run

```
git clone --recursive https://github.com/emilyhunt/clustering_algorithm_comparison.git
```

## Contents

* Notebooks - various things to play around with
* `hdbscan_issue_demo` - A demonstration of how HDBSCAN can fail on noisy data due to various algorithm flaws (despite being a very sensitive and useful algorithm in other ways)
* `nam_2022_clustering_algorithm_talk` - slides and an example notebook from a talk I did at the National Astronomy Meeting 2022 at the University of Warwick. This is a nice little intro to the topic!

