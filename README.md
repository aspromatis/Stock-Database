# How to create a PostgreSQL stock database using Python

This code example will help you create your own stock pricing database using PostgreSQL and Python.  The code will create two separate tables:

daily_prices:  A table containing daily OHLCV stock pricing information (pkey:  symbol, date)

tickers:  A table containing detailed information on each ticker/symbol in the daily_prices table (pkey: symbol)

Note:  The database password is stored as an environmental variable.

## Database Requirements

Download and install [PostgreSQL](https://www.postgresql.org/)

Download and install [pgAdmin](https://www.pgadmin.org/)

Create a new database instance in pgAdmin, name the new database 'stockdata'

## Python Requirements

Download and install [Anaconda](https://www.anaconda.com/products/individual)

Create a new virtual environment

`$ conda create --name polyenv python=3.8`

Activate the new virtual environment

`$ conda activate polyenv`

Install packages

`$ pip install -r requirements.txt`

Alternatively, you can take a look at the requirements.txt file and install what you need.

Note, I'm using VS Code with the ipykernel (Jupyter Notebook) capability to run in a notebook like experience.  You can certainly also run this without this.


Additional instructions on my [YouTube channel](https://www.youtube.com/c/ErolAspromatis)