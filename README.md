# Lab 12 - Data Analysis with Pandas (BIKE STATS)

**Author**: Kassie Bradshaw

**Version**: 1.0.0

---

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 401 class. (i.e. What's your problem domain?) -->

Today we're taking a tour into Data Science to learn a bit more about the field and tools used in this space!

The best way to hone your data analysis skills is consisten, deliberate practice. One of the best places to acquire data for analysis is [Kaggle](https://www.kaggle.com/), so practice your abilities with some [Kaggle Data Sets](https://www.kaggle.com/datasets).

Sign up for a Kaggle account (if you don't already have one).

---

## Feature Tasks

* [ ] Find and download the [Cycle Share](https://www.kaggle.com/pronto/cycle-share-dataset) Data Set - Bicycle Trip Data from Seattle's Cycle Share System

* [ ] Start a Jupyter Notebook called `bike-stats`
* [ ] Add a markdown cell at the top of the notebook with the title of this assignment, an appropriate name for the data set, as well as your name and the date
* [ ] Load up the Data Set into a Pandas DataFrame within the respective file

---

## Requirements

Answer the following questions/do the following tasks:

[ ] 1. What is the average trip duration for a borrowed bicycle?

[ ] 2. What's the most common age of a bicycle-sharer?

[ ] 3. Given all the weather data here, find the average precipitation per month, and the median precipitation.

[ ] 4. What's the average number of bikes at a given bike station?

[ ] 5. When a bike station is modified, is it more likely that it'll lose bikes or gain bikes? How do you know?

[ ] 6. Come up with 3 more questions that can be answered with this data set

---

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->

* Create a directory for the project on your local machine
* Move into the directory
  * ( Run `cd <directory you created`> )
* Copy my code link from GitHub: <https://github.com/kassiebradshaw/bike-stats.git>
* Clone to your desired directory on local machine
  * ( Run `git clone <paste-the-link-you-copied>` )
* Run `poetry install` (to install dependencies)
* Run `poetry shell` (to start virtual environment)

---

## Architecture

<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. This is also an area which you can include any visuals; flow charts, example usage gifs, screen captures, etc.-->

---

## API

<!-- Provide detailed instructions for your applications usage. This should include any methods or endpoints available to the user/client/developer. Each section should be formatted to provide clear syntax for usage, example calls including input data requirements and options, and example responses or return values. -->

---

## Change Log

**07-13-2021:**

* Created Jupyter Notebook and README
* Created GitHub repo
* Initial ACP

## Credit & Collaboration

* Had an issue reading the trip CSV file, used [this stack overflow link](https://stackoverflow.com/questions/18039057/python-pandas-error-tokenizing-data) to help find the solution to add a semicolon seperator to the read function
