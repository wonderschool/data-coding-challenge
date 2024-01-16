# Wonderschool data-coding-challenge

## Introduction

Thanks for your interest in joining the Wonderschool data team! Before we proceed with more formal interviews, we ask that all candidates submit a python coding challenge. The coding challenge is a foundational piece of our process, and can be referenced later in our process, during the technical interviews.

For an experienced data engineer, with the Python experience we are looking for, the coding challenge should not take longer than **1-2 hours** to complete.  We will evaluate the code for completeness as well as the logic contained within.

If at any point you have questions concerning this challenge and/or interview process, please do not hesitate to email data@wonderschool.com.

## Challenge

The data coding challenge revolves around processing of data using Python. Attached in this repository you will find a data file called data.json.  The data file is a list of records from a fictitious sales challenge in which we need statistics for.  The file contains a few duplicates that must be deduped to get the final resultset as well.  The challenge is to create a python script, that parses the data.json file, and creates a final resultset json file called result.json.  

The calculations and structure of this **single json object** should be as follows:

* Total Number of unique participants (total_participants)
* Total Number of unique participants in each age group (participants_group_X, with X being age group's id) 
* Average score of each age group (avg_score_group_X, with X being age group's id)
* Number of records removed from each age group (dupes_removed_group_X, with X being age group's id)  

In the event a duplicate exists by id, the highest score should be used, and the lowers discarded.  The id in each record should be used as the duplication identifier.    This resultset should be a single json object and include the following calculations:

## Getting Started

- To get started, clone this repo to your local machine.
- Next you'll want to open your favorite IDE and open the app.py file to get started.
- The input and output files have been opened and closed for you automatically.
- Add your code after the comment in code telling you to do so.
- Feel free to comment your code on any non-obvious action performed.

## Submission

To submit your coding challenge, save and execute the script, to generate results.  Then zip the whole data-coding-challenge folder and send it to data@wonderschool.com with the subject:

**<Your Name> Data Coding Challenge Submission**

We do our best to review and respond to submissions within 1-2 business days and someone should be contacting you within that timeframe.

Thanks for taking the time to do this python challenge and good luck!