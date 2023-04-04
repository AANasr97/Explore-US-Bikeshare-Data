# Explore US Bikeshare Data
 
# US Bike Share Data Analysis
This project analyzes the data related to bike share systems for three major cities in the United States: Chicago, New York City, and Washington. Using Python, this project provides descriptive statistics about bike share use in these three cities, including the most common times of travel, the most popular stations and trip, the average trip duration, bike use patterns, and other key insights.

## Getting Started
### Prerequisites
In order to run this project, you need to have Python installed on your computer, as well as the following libraries:

- pandas
- numpy
- time

### Installing
Clone the GitHub repository and open the project in your Python environment of choice.

## Running the Program
After setting up the project, you can run the bikeshare.py file in your Python environment to execute the program. When you run the program, you will be prompted to enter the name of the city you want to analyze data for, as well as any filters you want to apply to the data.

The program then loads the data for the specified city and filters it based on user input. Once the data is loaded, the program provides various descriptive statistics and insights about bike share use in the city.

## Program Details
The program is divided into several functions:

- `get_filters()`: This function prompts the user to specify a city, month, and day to analyze, and returns the user's input.
- `load_data(city, month, day)`: This function loads the data for the specified city and filters it based on the user's input for month and day.
- `time_stats(df)`: This function displays statistics about the most frequent times of travel.
- `station_stats(df)`: This function displays statistics about the most popular stations and trips.
- `trip_duration_stats(df)`: This function displays statistics about the total and average trip duration.
- `user_stats(df)`: This function displays statistics about the demographics of bike share users.

The program also includes error handling to ensure that user input is valid, and provides the user with helpful prompts throughout the program.