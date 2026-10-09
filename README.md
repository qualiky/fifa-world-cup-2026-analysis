# FIFA World Cup 2026 Analysis
A bit of analysis on 2026 FIFA World Cup data. No specific goal in mind, we update this document as we go. Assignment for HIT140, CDU.

## Data Source

1. FbRef: I tried digging into fbref - great source of data, great for spot check but I am not downloading all that data manually. Also already has cloudflare in the front, won't scrape it, gotta respect their T&C.

2. The Stats Don't Lie: Same issue. Good for spot check, no API, don't want to scrape. Data is behind a paywall. No bueno.

3. FIFA: Good for spot check, no API. The data density for scrapping is horrible. Won't do that.

Searched Kaggle, ended up with [Mominullptr's dataset](https://github.com/mominullptr/FIFA-World-Cup-2026-Dataset.git)

## Data Exploration

First, I want to explore the original data and see what it is like. Too many CSV files - the repo already has a [method](https://github.com/mominullptr/FIFA-World-Cup-2026-Dataset.git data/fifa-2026) to create a SQLite database out of it.

Based on the dataset that is available, we directly load up csv files into pandas dataframes and use it to populate charts. The Exploratory Data Analysis, along with statistical methods and formulas help us understand the type of data we are dealing with.

# How to run

The application requires Python (3.10 or higher). To run,

1. Install `uv` (the Python package manager). Instruction to install uv [here](https://docs.astral.sh/uv/getting-started/installation/).
2. Clone this repository to your machine and open the code folder in your terminal of choice.
3. Run `uv init` and `source .venv/bin/activate`. Once the virtual env is activated, run `uv add` and `uv sync` to download and sync the packages to your machine.
4. Once done, run `uv run jupyter lab` - this will start the Jupyter Notebook.

In case of confusion, you can reach out to me via Teams.
