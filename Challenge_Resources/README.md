# Detailed Instructions From Your Instructor Team

The objective of this challenge is for you to use PySpark to perform ETL on an Amazon review dataset, store the results in an AWS RDS pgAdmin database, and then use PySpark, Pandas or SQL to determine if there is any bias towards favorable reviews in the chosen dataset. Then, you'll write a summary of the analysis.

## Deliverable 1: Perform ETL on Amazon Product Reviews

For the first deliverable, we are asking you to pick a dataset from the [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), extract the dataset into a DataFrame, transform the DataFrame into four separate DataFrames that match the table schema [table schema](./Resources/challenge_schema.sql), and then upload the transformed data into the appropriate tables in pgAdmin.

you should not find the tasks in this deliverable to be difficult since extraction, some of the transformation steps, and the loading were covered in Lessons 16.7.2, 16.7.3, and 16.9.1.

We have provided [starter code](./Resources/Amazon_Reviews_ETL_starter_code.ipynb) to assist you with the steps needed to perform the transformation and loading. 

## Deliverable 2: Determine Bias of Vine Reviews

For the second deliverable, you will use PySpark, Pandas, or SQL to determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis you'll determine if there are differences in the percentage of 5 star reviews where there is a written Vine review (i.e., paid) compared to where there isn’t a written Vine review (i.e, unpaid). 

We recommend that you use PySpark or Pandas if your SQL skills are limmited. Some of the analysis more challenging using SQL than PySpark or Pandas. 

There is no starter code for this deliverable, however we have provided some general steps to perform the analysis.

## Deliverable 3: A Written Report on the Analysis

The goal of the writing assignment is for you to present your findings in a logical manner. As a reminder, you should use appropriate grammar and structure when writing.

For this deliverable you will write a report that summarizes the analysis performed in Deliverable 2.

For the written analysis, you will write a report that summarizes the analysis performed in Deliverable 2. The report will be written in the repository README.md and contain three sections: an overview of the analysis, results, and summary. 

**Overview of the analysis:** Explain the purpose of this analysis.

**Results:** Using bulleted lists and images as support, you should address the following questions.

* How many total reviews were there for a review that was or wasn’t written as part of the Vine program?
* How many 5 star reviews were there for a review that was or wasn’t written as part of the Vine program?
* What is the total percentage of 5 star reviews for or a review that was or wasn’t written as part of the Vine program?

**Summary:** In the summary, you should state whether there is any bias in the Vine program. They should use the results of your analysis to support your statement, and provide one additional analysis that they could do with the dataset to support your statement. 

The README.md document should be in the home directory of your repository. All links should be working, and images should be formatted and displayed where appropriate.

## Submission

Make sure they upload the following to your Amazon_Vine_Analysis GitHub repository:

1. your `Amazon_Reviews_ETL.ipynb` file.
2. your `Vine_Review_Analysis.ipynb` or `Vine_Review_Analysis.sql` file.
3. An updated README.md that has your written analysis.

## Grading Rubric

The [Big Data Grading Rubric](./Resources/Module_16_Challenge_Grading_Rubric.pdf) is provided for you to use when grading you' submissions.
