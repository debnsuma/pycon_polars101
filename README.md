# <h1 align="center"><strong> 🐻‍❄️ Welcome to Polars Workshop on AWS 🐻‍❄️</strong> </h1>

![polars](/img.png)

## Introduction

In this workshop we will start with [**Polars**](https://pola-rs.github.io/polars-book/) basics and shall compare with Pandas DataFrame, and shall walk through code exploring functions and features of Polars, for example load and transform data from CSV, Excel, or Parquet, perform data analysis in parallel and prepare your data for machine learning pipelines and shall compare with **Pandas** and **Spark**. 

We focus more on the following, which makes Polars special:

- parallel hashing
- lazy execution
- expresive API

We are going to use **Amazon SageMaker Notebook** as our working environment, and you may like to use any environment of your choice. 



## Getting started

If you are using local environment, please make sure you perform the following steps before getting started 

```bash
git clone https://github.com/debnsuma/pycon_polars101.git
cd pycon_polars101
chmod +x pip-deploy.sh
./pip-deploy.sh
source polar_env/bin/activate
cd notebooks
jupyter lab
```

Follow all the sections one after another under the **`notebooks`** folder 
