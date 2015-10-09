# NetApp

Brian McKean from NetApp presented to the class a data analysis problem he'd
like to get some help on.

# Overview

Listen to his presentation carefully. Write down the answers to the following
questions to show your team's understanding of the basics of the problem.

## What is the problem?
The problem is that the observation time data is very skewed and glitchy.


## Why is the problem important?
If the ASUPs aren't giving good information, then he cannot work on optimizing the system.


## What dataset has been made available?
A dataset based on observation time, delta time, firmware and software updates, and base time for the system.


## What specific questions are being raised?


# Q/A session

We will run a Q/A session. Before the session, compile a list of questions you
want to ask. Then, teams will take turn to ask Brian follow up questions.
Each team gets to ask one question each time. Write down the questions your team
wanted to ask and the answers you received. If another team happens to ask the
same question, simply write down the answer you heard.

## Is there any extra data to use?
No, there is no extra data to interpolate.

## What is the ideal behavior of the systems?
One ASUP per day per system.


## Is there any known bug in the observation time data?
There is only a bug known in base time, not observation time.


# Approach

Based on the information you've obtained during the Q/A session, come up with
plan how your team will tackle this problem.

## How should the dataset be imported into Tableau?
It should be imported in a CSV file.


## How should the work be distributed among the team members?
Everyone should do their own visualization and then come together to see what is wrong in the data.


## What types of charts or visualizations will be used to support the answer?
Bar charts, scatter plots, pie charts, etc.


## What questions may be too complex for Tableau and may require custom scripts to be written?
Any question that would require more than 2 or 3 columns in the data file to interpolate and visualize data.
