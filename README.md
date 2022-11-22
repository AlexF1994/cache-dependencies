# How to speed up your CI pipelines
This repo implements six different strategies for setting up a Python environment in your CI pipeline in order
to compare how fast these are for installing your dependencies.

The different strategies are:

* Use pip as package manager
* Use pip but cache dependencies between runs
* Use conda as package manager
* Use conda but cache dependencies between runs
* use mamba as package manager
* Use mamba but cache dependencies between runs

You can find the results of the CI pipelines [here](https://github.com/AlexF1994/cache-dependencies/actions).

## Resources
* [Blog post](https://dev.to/epassaro/caching-anaconda-environments-in-github-actions-5hde) by [epassaro](https://dev.to/epassaro) for caching mamba
* [official documentation](https://github.com/marketplace/actions/setup-miniconda#example-6-mamba) for conda strategies
* [Github actions documentation](https://github.blog/changelog/2021-11-23-github-actions-setup-python-now-supports-dependency-caching/) for pip caching

## Contact
Alexander Fottner a.fottner@googlemail.com