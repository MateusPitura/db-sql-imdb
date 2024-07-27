<h1 align="center"> 
  <p>IMDb Dataset for MySQL</p> 
</h1> 

<p> 
  <img src="https://img.shields.io/badge/Release-July%202024-green">  
  <img src="https://img.shields.io/github/stars/MateusPitura/db-sql-imdb?style=social"> 
</p> 

> :checkered_flag: This project is finished :checkered_flag:  

## Description

This repo contains a dump of MySQL with **407,431** movies, **1,252,264** people, and more, all related. The goal is to provide a large dataset for computer science students to compare queries and their efficiency

The data was downloaded from [CS50](https://cs50.harvard.edu/x/2023/psets/7/movies/), a course at Harvard University. The data was in SQLite3, but has been converted to MySQL for ease of use. It's possible to download the original data from the [IMDb site](https://developer.imdb.com/non-commercial-datasets/)

## Índice 

- [Features](#features) 
- [How to use](#how-to-use) 
- [Technologies used](#technologies-used) 
- [Authors](#authors) 

## Features 

:bank: **MySQL:** the data can be used in MySQL

:movie_camera: **Real data:** real data from IMDb with relationship between them

:pencil2: **Diagram:** a diagram to make it easy to understand 

## How to use

**For devs:** it takes about 1 minute to import all the data

1. `git clone git@github.com:MateusPitura/db-sql-imdb.git dump`

2. `mysql -u <username> -p`

3. `CREATE DATABASE imdb;`

4. `exit`

5. `cd ./dump`

6. `mysql -u <username> -p imdb < imdb.sql` 

## Technologies used

:heavy_check_mark: MySQL

## Authors 

| Mateus Pitura | 
|------| 
| <p align="center"><img src="https://user-images.githubusercontent.com/119008106/227821967-fac62c31-0d62-485b-829e-ef56c033e21a.jpeg" width="100" height="100"></p> | 
| <a href="https://www.linkedin.com/in/mateuspitura/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"> |
