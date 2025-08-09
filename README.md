Project 1: Analysis Of US Bikeshare Data From Motivate
======================================================
### by Arnabi Saha

Overview:
-------------------------------------------
This project analyzes the bike-share data of US from [Motivate](https://www.motivateco.com/) for popular cities Washington, New York, and Chicago; and then shows various statistics according to filter chosen by user.

Moreover after seeing statistics of a particular station, the user can restart the program to see the statistics of another station or same station with different filters.

### Available Filters

**Day:** This filters the data by day.\
**Month:** This filters the data by month.\
**Both:** This filters the data by both month and year.\
**None:** This does not filter data at all.

*If filter is day, month, or both, then statistics of popular day, month or both are shown respectively before filter is applied.*

### Statistics Shown

These statistics are shown on filtered data:~

**Time statistics:** This shows statistics of most popular day of travel, most popular month of travel, and most popular hour of travel. *However if data is filtered by day, month or both, then statistics on most popular day, month or both is shown on whole data set instead of showing it on filtered data-set.*

**Station Statistics:** This shows statistics of the most common Start Station, most common End Station, and most popular trip based on combination of Start and End Stations.

**Trip Duration Statistics:** This shows statistics of the total trip duration and the average trip duration.

**User Statistics:** This shows statistics on the types of bike users, gender of bike users, most recent, most common, and most earliest birth year of the bike users.

## Activate virtual environment first:
- After cloning the repo run command ```uv .venv``` to create virtual environment
- To activate virtual environment: ```source .venv/Scripts/activate```

## Required Libraries and Dependencies:

Python 3.x is required to run this project. The Python executable should be in your default path, in which the Python installer should have set. 

To install the above packages(*if not installed*) open terminal or command prompt and type in the command 
```
uv sync
```

## Project contents:

This project consists for the following files:

* **bikeshare.py** - main Python script to run.
* **chicago.csv** - contains bikeshare data for Chicago city.
* **new_york_city.csv** - contains bikeshare data for New York city.
* **washington.csv** - contains bikeshare data for Washington city.
* **README.md** - Readme file containing detailed instructions for program execution and project overview.
* **_config.yml** - Configuration file for github theme.

## Download:
This project can be downloaded by [clicking here](https://github.com/arnabisaha/US_bikeshare_data_analysis/archive/master.zip) 

## How to Run Project:

Download the project zip file to your computer and unzip the file. Or clone this repository to your desktop by typing the following code in your terminal(*for Linux*) or command prompt(*for windows*):

```bash
git clone https://github.com/arnabisaha/US_bikeshare_data_analysis.git
```

Navigate to the project directory and type in the following command:

```bash
python main.py
```

or

```bash
uv run main.py
```

## References:
1. [Markdown formatting for README.md](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
2. Clearing the screen: [Stack Overflow Link](https://stackoverflow.com/questions/2084508/clear-terminal-in-python)
3. Counting grouped occurences in dataframe: [Stack Overflow Link](https://datascience.stackexchange.com/questions/29840/how-to-count-grouped-occurrences)

Thank you.
"# US_bikeshare_data_analysis" 
