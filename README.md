# Project 1: 200 countries, 200 Years, 4 Minutes

## Introduction
This project, "200 countries, 200 Years, 4 Minutes" reproduced the famous data visualization project, [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo&pp=0gcJCdgAo7VqN5tD&themeRefresh=1).

It establishes the data base using `pandas` and `sqlite3`, utilizes `matplotlib` for proof-of-concept, and finally  adopts `plotly.express` for the final visualization.

## Reproduce

- Install [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions)
- Set up your environment based on `environment.yml` using the command"  

```bash
conda env creat -f environment.yml
```
- Save the CSV files in `data` folder
- Run `python creat_gapminder_db.ipynb` under the environment to create `gapminder.db` in the `data/` folder
- Run `python plot_with-px.ipynb` under the environment to generate the final visualizations. 