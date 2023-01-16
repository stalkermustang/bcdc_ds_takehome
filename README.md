# Blockchain.com Data Scientist TakeHome (February 2022)
Solution by [*Kotenkov Igor*](https://www.linkedin.com/in/seeall/)

## Description
This task is about forecasting how many bikes are rented from the [TFL (Transport for London)](https://en.wikipedia.org/wiki/Transport_for_London) Cycle Hire scheme.

Specifically, a candidate should attempt to answer the question **“Can national electrical power generation help estimate how many bikes are hired?”**

The idea is that these two datasets **may be correlated** with data we don’t have information on (e.g., the weather).

## Included Data Sources (in the [data](data/) folder):
1. [tfl-daily-cycle-hires.xlsx](data/tfl-daily-cycle-hires.xlsx): the daily number of hired bikes. Downloaded from [London Datastore](https://data.london.gov.uk/dataset/number-bicycle-hires);
1. [electrical_power_data.csv](data/electrical_power_data.csv): the daily amounts of produced energy (by source). Downloaded from [REF](https://ref.org.uk/) using the following pattern: https://www.ref.org.uk/fuel/index.php?valdate=2009&tab=dp&share=N (Substituted “2009” in the URL to get data for later years);
1. A candidate may also use other data sources (e.g., the attached Bank Holidays [ukbankholidays.csv](data/ukbankholidays.csv)).

## Deliverables
**Note**: A clear methodology supported by reasonable justifications is more important than an extremely accurate model.

### The solution should include the following:
1. Some preliminary data exploration;
1. A model which predicts TFL Cycle Hire numbers using ONLY the TFL dataset;
1. A model which predicts TFL Cycle Hire numbers using the TFL and electrical power generation dataset.

### A candidate can use any model(s). However, they should:
1. Give reasons for their choices;
1. Outline how/why they selected the features which were used as inputs;
1. Evaluate their model(s) through multiple metrics.

A candidate should produce a [Jupyter Notebook with the solution](Blockchain%20HW.ipynb). Here in the repository, you can also check [the HTML version](Blockchain%20HW.html) (easier to open in a browser).

Blockchain.com generally expects candidates to spend around 3 hours on the task, depending on their availability.

Please note that I, the author of this solution (not the whole TakeHome), spent ~8 hours on the attached solution. However, I spent most of the time on notes/descriptions and their proper (and the best possible) English translation.
