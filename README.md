# Reddit Churn Analysis

<img src='https://www.adweek.com/wp-content/uploads/2019/10/Reddit-Logo-Horizontal.png.webp' width='359' height='200'>

## Project Description
This repository is for the team project **MSCA 37014 Python for Analytics**.
* Instructor: `Shahbaz Chaudhary`
* Authors: 
  * `Zoila Joyo Calderon`
  * `Lauren Sample`
  * `Ruobing Xue`
  * `Elly Yang`

## Data Description
`RC_2012_year_cohort.feather` contains data from Jan 2012 to Nov 2012 with the following three variables:
* `author`: the user name of the person writing the comment
* `created_utc`: the timestamp of the comment
* `subreddit`: the name of the subreddit where the author posted a comment

## Executive Summary
Churn or retention analysis is a popular tool to measure the engagement of users. Given an initial interaction, we can track clients' interactions over days/weeks/months by aggregating all interactions on day 0, day 1, day 7, day 30, day 365, etc. The resulting series gives us an overview of how interactions are evolving over time. For the purpose of this project, the interaction we will look at is how often authors are commenting. Containing tens of thousands of subreddits where people discuss almost any topic imaginable, Reddit is one of the most popular websites. We will segregate analysis by top 10 subreddits and visualize if one subreddit is more `sticky` than another subreddit. Since our analysis will be done on a relative time basis, the date on which an author posted their first comment to a subreddit will serve as our day 0.
