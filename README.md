#### Data Analysis with Pandas; seattle-401pyn2
### Seattle Bike Trip Stats
- Kim Damalas, 20 Jan 2021
- using stats from [Kaggle](https://www.kaggle.com/pronto/cycle-share-dataset): station.csv


Submission pull request: 

## Description
___________

Taking a tour into Data Science to learn a bit more about the field and tools used in this space
____________
## Feature Tasks and Requirements
___________

Answer the following questions/do the following tasks. 
1. What is the average trip duration for a borrowed bicycle?
2. What’s the most common age of a bicycle-sharer?
3. Given all the weather data here, find the average precipitation per month
    -  and the median precipitation.
4. What’s the average number of bikes at a given bike station?
5. When a bike station is modified, is it more likely that it’ll lose bikes or gain bikes? How do you know?
6. Come up with 3 more questions that can be answered with this data set.
    - this question
    - this question
    - this question

______________

## Configuration and Technologies
__________

The user must have Python and all associated dependencies installed.  The project is run inline using a Jupyter notebook
___________
## Changes
__________

20 Jan: files set up; grid coded; first PR
___________

## Testing
________
Testing accomplished using inline testing. The program must pass the provided tests given in the file as well as any custom tests coded by the developer
```
def test():

    def assert_equal(actual,expected):
        assert actual == expected, f"Expected {expected} but got {actual}"

    assert_equal(avg_trip, None)
    assert_equal(most_common_age, None)
    assert_equal(avg_precip_month, None)
    assert_equal(median_precip, None)
    assert_equal(avg_bikes_per_station, None)
    assert_equal(lose_or_gain_bikes, None)

    -- test Q8.1
    -- test Q8.2
    -- test Q8.3

    print("Success!!!")

test()
```
____________

