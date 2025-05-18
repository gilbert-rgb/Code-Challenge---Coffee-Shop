# Code-Challenge---Coffee-Shop

## Overview
This project models a coffee shop using OOP principles in Python. It includes three main classes: `Customer`, `Coffee`, and `Order`.


We model a coffee shop with three main classes:

- **Customer** – someone who buys coffee
- **Coffee** – a type of drink sold at the shop
- **Order** – connects customers to coffees they’ve purchased, with a price


## Features
-
- A **Customer** can have many **Orders**
- A **Coffee** can have many **Orders**
- An **Order** belongs to one **Customer** and one **Coffee**

This forms a many-to-many relationship between `Customer` and `Coffee` through the `Order` model.

---

## Setup
```bash
git clone <git remote add origin git@github.com:gilbert-rgb/Code-Challenge---Coffee-Shop.git>
   
pipenv install
pipenv shell
pytest
