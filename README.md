# Project 1: 200 countries, 200 Years, 4 Minutes

## 👋 Introduction
This project, "200 countries, 200 Years, 4 Minutes," reproduces the famous data visualization project, [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo&pp=0gcJCdgAo7VqN5tD&themeRefresh=1).

It establishes the database using `pandas` and `sqlite3`, utilizes `matplotlib` for proof-of-concept, and finally  adopts `plotly.express` for the final visualization.

## ✨ Project Highlights　
1. This project uses a comprehensive dataset directly from gapminder.org, offering a much richer and more detailed analysis than the condensed versions often seen in examples (which typically cover only 1952-2007 with five-year intervals).
3. It generates the SQL plot that connects to multiple data files, significantly increasing flexibility for data manipulation.
4. The entire project is fully reproducible.
5. The final visualization is accessible via a [GitHub Page](https://crystochen.github.io/gapminder_clone/gapminder_clone.html).

## 📖 Reproduction Guide
- Install [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions)
- Set up your environment based on `environment.yml` using the command"  

```bash
conda env creat -f environment.yml
```
- Save the CSV files in `data` folder
- Run `python creat_gapminder_db.ipynb` under the environment to create `gapminder.db` in the `data/` folder
- Run `python plot_with-px.ipynb` under the environment to generate the final visualization `gapminder_clone.html`. 
