# Weather Trip Planner

A simple Python program that determines whether a commute is possible based on the travel distance, weather conditions, and available transportation options.

## Features

The program evaluates different situations based on:

* Travel distance in miles
* Whether it is raining
* Bicycle availability
* Car availability
* Ride-share app availability

## Rules

* **0 miles:** returns `False`
* **1 mile or less:** possible only if it is not raining
* **More than 1 mile and up to 6 miles:** possible only with a bicycle and no rain
* **More than 6 miles:** possible with a car or a ride-share app

## Concepts Practiced

* Variables
* Boolean values
* `if`, `elif`, and `else`
* `and`, `or`, and `not`
* Conditional logic
* Truthy and falsy values

## Technologies

* Python 3

## How to Run

```bash
python main.py
```

## Source

This project was completed as part of a FreeCodeCamp Python exercise.
