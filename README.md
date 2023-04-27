# censusdis-tutorial

Tutorial presented at [PyData Seattle 2023](https://pydata.org/seattle2023/).

## Quickstart on mybinder.org

*This is the quickest way to get started.*

Live interactive versions of the tutorial notebooks in this project, hosted on <a href="https://mybinder.org" target="_blank">mybinder.org</a>,
are available at the following links:

- Part I: <a href="https://mybinder.org/v2/gh/vengroff/censusdis-tutorial/HEAD?labpath=Tutorial.ipynb" target="_blank">Tutorial.ipynb</a>
- Part II: <a href="https://mybinder.org/v2/gh/vengroff/censusdis-tutorial/HEAD?labpath=Newark.ipynb" target="_blank">Newark.ipynb</a>
- Part III: <a href="https://mybinder.org/v2/gh/vengroff/censusdis-tutorial/HEAD?labpath=Project Template.ipynb" target="_blank">Project Template.ipynb</a>

These may take a minute or two to start up, but they will then be live and ready to go. You don't have to create any local environment or install
anything.

## Running on your own machine

If you would like to run the notebooks on your own machine, you will need a Python 3.9 virtual environment. In that virtual environment, you can then clone the repository with

```shell
git clone https://github.com/vengroff/censusdis-tutorial.git
```

Once the repo is cloned, enter it and install the requirements with

```shell
cd censusdis-tutorial
pip install -r requirements.txt
```

Now you start jupyter with

```shell
jupyter-lab
```

If all goes according to plan, this should fire up the server on your local machine and open a browser to let you explore and run the notebooks.
