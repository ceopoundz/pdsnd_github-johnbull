### April 26th, 2022
### Explore US Bikeshare Data
### This project asks users to select among three cities washinghton, chicago and new york city and filter data base on this selected city
### Files used includes data set from three cities washington new york and chicago all in csv format
### Extra resources used includes https://github.com/Aritra96, https://stackoverflow.com/questions/23294658,  https://classroom.udacity.com/nanodegrees/nd104/parts/cd0024/modules/1e4392d9-c759-42d1-8204-aaed736ae199/lessons/ls1727/concepts/ff725dae-97d7-4d8d-ab8b-9ca18c89aa48, https://classroom.udacity.com/nanodegrees/nd104/parts/cd0024/modules/1e4392d9-c759-42d1-8204-aaed736ae199/lessons/ls1727/concepts/7a33cce4-18de-48a4-8aeb-d0c13c972909
### Project code details
the bikeshare.py file used python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington.  Codes was written to import the data and answer interesting questions about it by computing descriptive statistics. The script  takes in raw input to create an interactive experience in the terminal to present these statistics.

the script takes users through the following stage
1. Asking user to chose from three cities from ( chicago, washington and new york city)
2. Asking user to filter data by a specific month from january to june or select all if no preference
3. Asking users to select a specific day from monday to sunday or all if no preference

the script was written to handle user input to ensure that user follows the recognised input to avoid breaking the program. The answers provided by users to the questions above will determine the city, the timeframe and which data analysis was done. After the result was provided the users were asked if they wanted to see the raw data and when they say yes more raw data would be generated and when they indicate no, the script promoted if they wanted to restart the program, a response of yes would mean they willl restart again and a response of no would mean they quit the program.