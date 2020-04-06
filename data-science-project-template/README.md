# Data Science Project Template

Whenever I begin a new data science project, whether it is for an existing company or a new consulting gig, I follow a similar workflow leading up to completion of the project.  This template is useful for successfully fulfilling the needs of the business stakeholders.  Note that many projects will stop at step 6, Reporting.  ML is only needed in certain cases.

1. Understanding the Business
2. What questions are we trying to answer?
3. Data Dictionaries
4. Query Library
5. Exploratory Data Analysis
6. Reporting
7. Opportunities for ML
8. Feature Generation
9. Exploring ML
10. ML Optimization
11. ML Reporting
12. Productionize
13. Review

## Understanding the Business

It is important to understand the domain the business operates in.  Answering these questions can help lay the groundwork for a successful engagement and provide insight into the data.

- What industry does the business operate in?
- How does the business make money?

## What questions are we trying to answer?

Understanding what questions the business is trying to answer is key to focusing the efforts of the data science project to best needs the needs of the business.  This is also a chance for the business to understand why it is embarking on this journey in the first place, what questions are already answered by existing data anlysis, and what questions they would like answered but don't have answers to now.

## Data Dictionaries

A tedious, but essential part of the process, is understanding the data.  Creating a data dictionary or set of dictionaries is key to learning about the data.  Here we want to ask several questions:

- What data is available and where?
- What do the individual fields of the data set(s) represent?
- What type of data is stored in each field?
- What is the history of that data and how has it changed over time?
- What are the raw sources of that data?
- What ETL is already being done to the data?

## Query Library

Once we have an understanding of the data and how we can access it, it is time to start building up a library of queries against the data.  Every query, whether through SQL or Pandas, should be stored for future use and review.  Even one-off queries need to be archived.  They will be needed again, even if only to reproduce previous reports.

## Exploratory Data Analysis

Now comes the fun part.  Here we get to dig in deep into the data and understand its strengths and shortcomings.  Key parts of this step include:

- Understanding of the features available in the dataset.
- Understanding of the data types stored in those features.
- Exploration of missing data and null values.
- Imputation or removal of missing data.
- Exploration of outliers.
- Initial look into categorization of values.
- Generation of reports on data.

## Reporting

In this phase, we try to see if the business questions identified earlier can be satisfied with existing data.  If so, we determine what the best report mechanism is for the audience.  This will likely entail visualizations as well as textual summaries of data.  Can be as flat as a pdf report with visualizations intended for business stakeholders, or it can be as complex as a reporting/visualization tool or set of scripts for sophisticated users.

## Opportunities for ML

Here were explore whether Machine Learning is a good fit for the business questions being answered, whether the data is a good fit for ML, and what ML algorithms may make sense for the task.  We don't actually do any ML in this phase, only ask whether ML is needed and appropriate.

## Feature Generation

Here we get our data ready for ML.  Important features are identified and categorized.

## Exploring ML

Based on our feature set and business questions, we begin exploring and identifying ML algorithms to test for fit to the task at hand.  Is this a classification task?  Is the data in the form natural language text or images?

## ML Optimization

Once we have an approach that appears to satisfy the needs of the business, then we begin optimizing it to get as much as possible out of our approach.  This can include such activities as ensembling of different ML algorithms.

## ML Reporting

Here we report on our approach, our efforts toward optimization, and our results using ML.  

## Productionize

If our efforts have produced meaningful results, we then work with the business to productionize the ML workflow and integrate into their existing systems.  

## Review

Once in production, the results of a system need to be reviewed and possibly re-optimized based on "real world" data and evolving data.


