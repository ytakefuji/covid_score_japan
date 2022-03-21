# Scoring covid-19 policies by prefecture in Japan
This is under review.

# How to install jpscore
You need pandas and openpyxl library.

$ pip install pandas

$ pip install openpyxl

On WSL on Windows, MacOS, or Linux operating systems, run the following command:

$ pip install jpscore

On Windows 11 or 10

$ pip install jpscore --force-reinstall --no-cache-dir --no-binary :all:

The latest data on the number of deaths by prefecture in Japan is at the following site:

https://www3.nhk.or.jp/n-data/opendata/coronavirus/nhk_news_covid19_prefectures_daily_data.csv

# How to run jpscore
The result.csv will be generated by the following command:
as of march 19, 2022

$ jpscore

<img src='https://github.com/ytakefuji/covid_score_japan/raw/main/result.png' width=397 height=1393>

# Exercises
<pre>
1. Make a csv file of the total deaths by prefecture using the latest data.
Hints:
Use pandas DataFrame.
Prefecture deaths population score
...

Find the latest date on the total deaths by prefecture in the csv file.
Make a list of prefectures.
Make the total deaths data by prefecture.
Find the latest population csv.
Make the latest population by prefecture.
Calculate a score by prefecture.

