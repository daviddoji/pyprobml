# pyprobml

<img src="https://img.shields.io/github/stars/probml/pyprobml?style=social">


Python 3 code to reproduce the figures in the book series [Probabilistic Machine Learning](https://probml.github.io/pml-book/) by Kevin Patrick Murphy.
This is work in progress, so expect rough edges.
(For the latest status of the code,
see [Book 1 dashboard](https://github.com/probml/pyprobml/blob/workflow_testing_indicator/dashboard_figures_book1.md)
and [Book 2 dashboard](https://github.com/probml/pyprobml/blob/workflow_testing_indicator/dashboard_figures_book2.md).)

See also [probml-utils](https://github.com/probml/probml-utils) for some utility code.

## Running the notebooks


The notebooks needed to make all the figures are available at the following locations.

* [All notebooks (sorted by filename)](https://probml.github.io/notebooks)
* [Book 1 notebooks (sorted by chaper)](https://github.com/probml/pyprobml/tree/master/notebooks/book1)
* [Book 2 notebooks (sorted by chapter)](https://github.com/probml/pyprobml/tree/master/notebooks/book2). 



### Running notebooks in colab

[Colab](https://colab.research.google.com/notebooks/intro.ipynb) has most of the libraries you will need (e.g., scikit-learn,  JAX) pre-installed, and gives you access to a free GPU and TPU. We have a created a 
[colab intro](https://colab.research.google.com/github/probml/pyprobml/blob/master/notebooks/tutorials/colab_intro.ipynb)
notebook with more details. To run the notebooks on colab in any browser, you can go to a particular notebook on GitHub and change the domain from `github.com` to `githubtocolab.com` as suggested [here](https://stackoverflow.com/a/67344477/13330701). If you are using Google Chrome browser, you can use ["Open in Colab" Chrome extension](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo) to do the same with a single click.

## Running the notebooks locally 

We assume you have already installed [JAX](https://github.com/google/jax#installation) and
[Tensorflow](https://www.tensorflow.org/install) and [Torch](https://pytorch.org/),
since the details on how to do this depend on whether you have a CPU, GPU, etc.

You can use any of the following options to install the other requirements.

* Option 1

```bash
pip install -r https://raw.githubusercontent.com/probml/pyprobml/master/requirements.txt
```

* Option 2

Download [requirements.txt](https://github.com/probml/pyprobml/blob/master/requirements.txt) locally to your path and run

```bash
pip install -r requirements.txt
```

## GCP, TPUs, and all that

When you want more power or control than colab gives you,
you should get a Google Cloud Platform (GCP) account
(or you can use some other cloud provider, like Paperspace)
to get a virtual machine with GPUs or TPUs.
You can then use this as a virtual desktop which you can access via ssh from inside VScode.
We have created [a short tutorial on Colab, GCP and TPUs](https://github.com/probml/pyprobml/blob/master/notebooks/tutorials/colab_gcp_tpu_tutorial.md) with more information.


## How to contribute

See [this guide](https://github.com/probml/pyprobml/blob/master/CONTRIBUTING.md) for how to contribute code. Please follow [these guidelines](https://github.com/probml/pyprobml/blob/master/notebooks/README.md) to contribute new notebooks to the notebooks directory.


## Metrics

[![Stargazers over time](https://starchart.cc/probml/pyprobml.svg)](https://starchart.cc/probml/pyprobml)

## GSOC 

For a summary of some of the contributions to this codebase during Google Summer of Code (GSOC),
see  these links: [2021](https://probml.github.io/pml-book/gsoc/gsoc2021.html)
and [2022](https://probml.github.io/pml-book/gsoc/gsoc2022.html).





<h2><a id="acknowledgements"></a>Acknowledgements</h2>

For a list of contributors, see
[this list](https://github.com/probml/pyprobml/graphs/contributors).
