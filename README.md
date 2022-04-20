# Data Exploration with pandas on Bikeshare Data
_A Python project using pandas to explore bikeshare data._

# Project Overview

This project focuses on pandas library usage and simple statistics methods to perform descriptive analysis on the bikeshare data from three major U.S. cities - Chicago, Washington, and New York City - to display information such as most popular days or most common stations.

### Running the program

You can input 'python bikeshare.py' on your terminal to run this program. I use Udacity WorkSpace privided run this project. The code also works fine using VS Code terminal after you must have installed all the requirement/dependencies.

### Program Details

The program takes user input for the city (e.g. Chicago), month for which the user wants to view data (e.g. January, February,..., June; also includes an 'all' option), and day for which the user wants to view data (e.g. Monday, Tuesday,..., Sunday; also includes an 'all' option).

Following the input received, the program prints the following details:

* Most popular month
* Most popular day
* Most popular hour
* Most popular start station
* Most popular end station
* Most popular combination of start and end stations
* Total trip duration
* Average trip duration
* Types of users by number
* Types of users by gender (if available)
* The oldest user (if available)
* The youngest user (if available)
* The most common birth year amongst users (if available)

Subsequently, it goes ahead and asks the user if they want to view the raw data for which the analysis was made (5 rows of data at a time) or not.

Finally, the user is prompted with the choice of restarting the program or not.

# Requirements

* Language: Python 3.6.3 or above
* Pandas : Version 0.23.3
* Numpy: Version 1.12.1
* Python time module: Comes preinstalled with python

# Project Data

* chicago.csv - Stored in the data folder, the chicago.csv file is the dataset containing all bikeshare information for the city of Chicago provided by Udacity.

* new_york_city.csv - Dataset containing all bikeshare information for the city of New York provided by Udacity.

* washington.csv - Dataset containing all bikeshare information for the city of Washington provided by Udacity. Note: This does not include the 'Gender' or 'Birth Year' data.

# Built with

* [Python 3.6.6](https://www.python.org/) - The language used to develop this.
* [pandas](https://pandas.pydata.org/) - One of the libraries used for this.
* [numpy](http://www.numpy.org/) - One of the libraries used for this.
* [time](https://docs.python.org/2/library/time.html) - One of the libraries used for this.

# Author

 * [Ogunlade Stephen Olayide](https://github.com/honordevop) 
  
# Acknowledgements

* [xhlow](https://github.com/xhlow) - xhlow's repository helped with understanding the structural details of certain functions required.
* [Aritra96](https://github.com/Aritra96/bikeshare-project) - Aritra96 repository helps in in understanding breakdown of the statistical steps required to achieve this project.
* [pandas docs](http://pandas.pydata.org/pandas-docs/stable/) - pandas documentation was immensely helpful in understanding the implemention of pandas methods used in this project.
* [Udacity](https://udacity.com) - Udacity's Data Analyst Nanodegree program and their instructors were extremely helpful while I was pursuing this project.
* [Udacity's_blog](https://www.udacity.com/blog/2014/04/how-to-make-python-program-wait.html#:~:text=If%20you've%20got%20a,want%20your%20program%20to%20wait.) - Teaches on how to delay code execution using python time module.
* Finally, I'd like to appreciate [Access Bank](https://www.accessbankplc.com/) and [Udacity](https://udacity.com) for this learning and self improvement opportunity.

