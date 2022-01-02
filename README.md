# Covid19_Study
This is a study of Covid 19 cases in the Nordic countries.

The study uses weekly based data in order to minimize the impact of how the different countries report the cases. Some contries only submit statistics at fixed intervals during the weeks. If we aggregate the cases on a weekly basis it is more likely to remove noise due to country specific reporting policies.

# Libraries used
The notebook uses the following libraries:
- Pandas
- Numpy
- Matplotlib
- Seaborn


# Data Source
Covid-19 data is collected from European Centre for Disease Prevention and Control.

Link: https://www.ecdc.europa.eu/en/covid-19/data


# Questions of interest

There are a number of questions that we want to find the answer to.

## Are the number of Covid-19 cases about the same throughout the Nordic countries?

If we look at the plot we can see that there are a lot of differences within the Nordic countries when it comes to the number of Covid-19 cases per 100k people, per week.

Finland and Norway are similar. Iceland has had a relative low number of cases throughout 2020 with a few short peeks. During the end of 2021 it got a major outbreak though.

Sweden and Denmark has shapes that are more unique, which probably depends on the different political measures taken during this time.

## Is there any particular country that has a higher occurrence of Covid-19 cases per week?

If we view the plot we can clearly see that Sweden has a much higher number of Covid-19 cases during the period 2020-41 to about 2021-20. After that period Sweden has instead a lower number of cases per week then the other Nordic countries.

Denmark has had a very high number of Covid-19 cases during the end of 2020 and again a very high peek at the end of 2021. No other country comes as high as Denmark does during the end of 2021.

## What is the correlation between Covid-19 cases by country?

When we look at the correlation heatmap we can see that most of the Nordic countries are highly correlated. The correlation coefficient is above about 0.7 for most country pairs.

One particular difference is however Sweden, that has a low correlation with the other Nordic countries. Even Iceland has a quite high correlation with the other Nordic countries, even though it is an isolated island.

