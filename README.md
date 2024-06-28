# Data Engineering Challenge: New York Taxi Data Processing

## Objective

This challenge is designed to evaluate your ability to handle large datasets, process and analyze data efficiently, and build robust data pipelines using modern data engineering tools. You will work with the New York Taxi Trip data set.

## Assignment Overview

You are tasked to design and implement a scalable data pipeline that extracts New York Taxi Trip data, processes it to derive analytical insights, and loads the processed data into a data warehouse for further analysis.

### Dataset
`Source:` [Trip Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). You will find the dataset categorized per year.

`Details:` The dataset includes fields such as pickup time, drop-off time, trip distances, fares, and passenger counts.

## Tasks

Data Extraction

Task: Automate the downloading of the dataset from the Year 2019.

Requirements:

    Write a script that downloads CSV files from the Year 2019.
    Ensure the script can handle network errors and retries.

Data Processing

Task: Clean and transform the data using Python and Pandas.

Requirements:

    Remove any trips that have missing or corrupt data.
    Derive new columns such as trip duration and average speed.
    Aggregate data to calculate total trips and average fare per day.

Data Loading

Task: Load the processed data into an SQLite database.

Requirements:

    Design and implement a schema suitable for querying trip metrics.
    Use SQL to load data into the database efficiently.

Data Analysis and Reporting

Task: Generate insights and reports from the database.

Requirements:

    Develop SQL queries to answer the following questions:
        What are the peak hours for taxi usage?
        How does passenger count affect the trip fare?
        What are the trends in usage over the year?
    Create visualizations to represent the findings.

Submission Guidelines

    Repository Setup:
        Create a new Git repository for this project.
        Ensure the repository is public to allow review.
        Use meaningful commit messages that explain the changes.

    Documentation:
        Include a README.md file that contains:
            Project Overview: A brief description of the project and its objectives.
            Environment Setup: Instructions on setting up the development environment, including any required software installations and dependencies.
            Running the Project: Step-by-step instructions on how to run your scripts and the data pipeline.
            Data Analysis: Explanation of how to query and visualize the data.

    Submission:
        Submit the link to your Git repository.

Deadline

    Submission Deadline: 7 days from the date of receiving the assignment.



## Submission Guidelines

    Repository Setup:
        Create a new Git repository for this project. The repository should be public to allow review by the hiring team.
        Follow a proper Git branching model. 

    Code and Commit Hygiene:
        Write clear, meaningful commit messages that explain the "why" behind each change.


    Submission:
        Submit the link to your Git repository to the HR department.
        Include any additional notes or comments that might help the evaluators understand the decisions made during the project development.

## Deadline

    Submission Deadline: 7 days from the date of recieving the assignment.

