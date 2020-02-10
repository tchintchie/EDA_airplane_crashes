# EDA_airplane_crashes
Exploratory Data Analysis of Airplane Crashes from Kaggle

I´d like to analyze and predict airplane crashes and the likelihood of surviving such a crash (although I couldn´t find any data on passenger seating so far). Goal is to answer the question wether flying really is the safest way to travel. Here is one dataset that might be of interest:

https://www.kaggle.com/saurograndi/airplane-crashes-since-1908

## Possible EDA tasks:
### 1. data cleaning:
#### 1.1: remove columns with 80 ore more percent of Null-values
#### 1.2:  check the `ground` column to see if it only contains `0` and `1`. If so convert it to a `Boolean` type

### 2. questions to answer:
#### 2.1: on avg. how many plane crashes happen per year?
##### 2.1.1: which year was the one with the least/most crashes?
#### 2.2: on avg. how many months are in between crashes?
##### 2.2.1: what was the longest period in between crashes?
#### 2.3: which `Operator` suffered the most crashes in history?

#### 3.1: from the `Route` column exract start and destination and create new columns for each
#### 3.2: what´s the most common weekday for crashes?
#### 4.1: on avg. how many passengers survive a crash (if any)? Create a new column called `survival rate`

## Bonus:
- What were the most common causes for crashes? Could be extraced from the `Summary`column (e.g. most common words)
- display the crash location on a map (might need longitude and latitude)
- categorize the `Type` column by maker (e.g. Boeing, Lockheed....)
- what´s the overall crash rate? (need to find data on total flights from 1908)

