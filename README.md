### General Info
***
Code for a variety of descriptiv statistics for the following statistics :

1. Popular times of travel 
  * most common month
  * most common day of week
  * most common hour of day 

#2 Popular stations and trip 
  * most common start and end station 
  * most common trip from start to end 

#3 Trip duration
  * total travel time 
  * average travel time 

#4 User info
  * counts of each user type 
  * counts of each gender (only for NYC and Chicago)
  * earliest, most recent, most common year of birth (only for NYC and Chicago)

### Technologies
***
A list of technologies used within the project:

+ [Numpy](https://numpy.org/install/)

+ [pandas](https://pandas.pydata.org/docs/getting_started/install.html)

+ [time](https://docs.python.org/3/library/time.html)

## Installation

A littel intro about the installation.

+ time is a built in modul in Python 3

+ use these commands to import the needed modules.
````
$ pip install numpy
$ pip install pandas
````

### Rules for the correct use of the program.
***
The code provides an interactive experience for the user.

1. Input handeling will ask for conformation if an spelling error occurs
2. a city input is needed
3. with entering all when asked for a specific day or month to apply no filter
4. with entering yes it is possible to get raw data shown ,even more if wished 
  * if no raw data should be shown entering no will result with the question for a restart
