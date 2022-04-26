# MLflow Demo + Model Review Overview

This repo contains materials for a talk on reviewing Machine Learning models before deploying to production, inspired by the concept of a Code Review. Most of the content is a tutorial on using [MLflow](https://www.mlflow.org/docs/latest/index.html) Tracking.

See either the Jupyter Notebook (tutorial.ipynb) for the content, or the html slides which were rendered using [RISE](https://github.com/damianavila/RISE). Current version of this talk was presented at [PyData SLC Meetup](https://www.meetup.com/PyData-SLC/events/283185065/) in January 2022, with the verbose title _"Model Review: improving transparency, reproducibility, & knowledge sharing using MLflow."_

### Getting Started

To try out the code examples in the notebook, you can create a conda environment from the yaml file (or install the dependencies listed there in your preferred way):

```
$ conda env create -f environment.yml
```
 
 Then activate the environment
 
 ```
 $ conda activate mlflow-demo
 ```
 
and try out some examples in the notebook. Enjoy!

### Rendering as slides with RISE

Optionally, if you want to use the [RISE](https://rise.readthedocs.io/en/stable/) extension on Jupyter Notebook, to view the notebook as slides, you might also need to run `jupyter contrib nbextension install --user`. Note that this extension
currently only works in jupter notebook, not jupyterlab. After starting
`jupyter notebook`, you should have a tab to configure `Nbextensions` including
RISE (I like to set the theme to `night`, the transition to `none` and check the box to enable `scroll` since some of these slides include large screenshots). In the notebook tab, you should have a button that looks like a barchart to `Enter/Exit RISE Slideshow`.
