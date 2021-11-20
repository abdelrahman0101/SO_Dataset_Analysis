# Are we home yet? Analyzing how Egyptian software developers work

This project shows an analysis of how Egyptian software developers responded to the StackOverflow survey questions related to remote work and freelancing.

This analysis is based on the results of StackOverflow surveys over the past three years; namely 2019, 2020 and 2021. Analysis over this time period gains interest since the emergence of Covid-19 have caused many organizations to shift to remote work and distributed teams, while many workers may have switched to freelancing and part-time jobs.

## Requirements
The code is implemented using Python in a Jupyter notebook. Datasets are obtained from the official StackOverflow survey archives for the years 2019, 2020, and 2021. Files were renamed to avoid conflicts.

This code uses the following python libraries:
* Pandas v1.3.0
* Numpy v1.21.4
* Matplotlib v3.5.0


## Project Structure:
1. SO_egypt_freelancing.ipynb:
This is the jupyter notebook containing all analysis code and generated charts.
2. datasets:
Dataset files are read from this directory. They were compressed into the datasets.zip file as they exceed the maximum size for files on Github.

## Results:
Statistics indicate that the percentage of Egyptian software developers who work in full-time jobs has decreased in 2021 compared to 2020, while the percentage of unemployed, freelancers, and part-time developers have increased.

In addition, comparing employment styles in Egypt with global statistics may indicate that Egyptian software developers have a lower job stability than global average. In 2021, for example, there is a relatively larger decrease in the ratio of full-time employees, which was already lower than global records. On the other hand, Egypt may also have a higher-than-average ratio of freelancers and independent contractors.

Analysis detailes for non-technical audience can be found [here](https://abdelrahman-hefny.medium.com/are-we-home-yet-analyzing-how-egyptian-software-developers-work-f07d208bd17)

## Acknowledgement
This project uses data obtained from StackOverflow surveys in the years 2019, 2020, and 2021. The original dataset archives can be found [here](https://insights.stackoverflow.com/survey).
