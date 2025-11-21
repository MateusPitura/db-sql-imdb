<h1 align="center"> 
  <p>IMDb Dataset for MySQL and Postgres</p> 
</h1> 

<p> 
  <img src="https://img.shields.io/badge/Release-Jul%202024-green">  
  <img src="https://img.shields.io/github/stars/MateusPitura/db-sql-imdb?style=social"> 
</p> 

## Description

This repo contains a dump of MySQL and Postgres with **407,431** movies, **1,252,264** people, and more, all related. The goal is to provide a large dataset for computer science students to compare queries

The data was downloaded from [CS50](https://cs50.harvard.edu/x/2023/psets/7/movies/), a course at Harvard University. The data was in SQLite3, but has been converted to MySQL and Postgres for ease of use. It's possible to download the original data from the [IMDb site](https://developer.imdb.com/non-commercial-datasets/)

## Índice 

- [Features](#features) 
- [How to use](#how-to-use) 
- [Technologies used](#technologies-used) 
- [Authors](#authors) 

## Features 

:bank: **MySQL & Postgres:** the data can be used in MySQL and Postgres

:movie_camera: **Real data:** real data from IMDb with relationship between them

:pencil2: **Diagram:** a diagram to make it easy to understand 

## How to use

**For devs | MySQL:** it takes about 1 minute to import all the data

1. `git clone git@github.com:MateusPitura/db-sql-imdb.git dump`

2. `mysql -u <username> -p`

3. `CREATE DATABASE imdb;`

4. `exit`

5. `cd dump/`

6. `mysql -u <username> -p imdb < imdb-mysql.sql`

**For devs | Postgres:** it takes about 1 minute to import all the data

1. `git clone git@github.com:MateusPitura/db-sql-imdb.git dump`

2. `psql -U <username>`

3. `CREATE DATABASE imdb;`

4. `\q`

5. `cd dump/`

6. `psql -U <username> -d imdb -f imdb-postgres.sql` 

## Technologies used

:heavy_check_mark: MySQL

:heavy_check_mark: Postgres

## Authors 

| Mateus Pitura | 
|------| 
| <p align="center"><img src="https://avatars.githubusercontent.com/u/119008106" width="100" height="100"></p> | 
| <a href="https://www.linkedin.com/in/mateuspitura/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"> |
