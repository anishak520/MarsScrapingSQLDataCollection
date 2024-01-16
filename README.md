# Mars Scraping - SQL Data Collection
Scraping data about Mars news article and martian weather
## Project files
The code for the initial deliverable (Mars News) is found in part_1_mars_news.ipynb, while part_2_mars_weather.ipynb includes the code for the second deliverable (Mars Weather Data). The Cleaned_Data directory houses the sanitized data from Deliverable 2, stored in a CSV file. Additionally, the Output directory contains PNG exports of the analysis from Deliverable 2, which are also included in this README file.

# Answers to questions
## How many months exist on Mars?
The answer is 12 months from the data. The answer was obtained by extracting the number of unique values from the dataset.

## How many Martian days' worth of data are there?
There are 1867 Martian days (sols) worth of data.

## Which month, on average, has the lowest temperature? The highest?
As shown in the figure(avg_temp_per_month.png), the month with the lowest temperature is the third month. The one with the highest temperature is the eigth month.
The temperature range on Mars, based on this dataset, is -83 degC to -68 degC on average.

## Which month, on average, has the lowest atmospheric pressure? The highest?
As shown in avg_pres_per_month.png, the month with the lowest pressure is the sixth month. The one with the highest pressure is the ninth month.

## How many terrestrial days exist in a Martian year?
Number of days between temperature peaks is around 1500 - 820 = 680 terrestrial days (this is within around 1% of the real value of 687 days). This is illustrated in the figure below, where the red vertical lines indicate the location of the peaks used to estimate the duration of a martian year. Trial and error was used to obtain these points.

# Resources
Data Science Bootcamp materials and stack overflow were used in formation of code. Referenced Kaushik Karthikeyan (my brother) for debugging help.
