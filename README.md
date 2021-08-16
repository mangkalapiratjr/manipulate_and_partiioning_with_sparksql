# Partitioning Covid19 cases data using SparkSQL + AWS S3

**Steps**
1. Import Covid19 dataset from AWS S3 (using datasource from ourworldindata.org)
2. Check missing values
3. Fill missing values with 0 and calculate cumulative total cases and total deaths as new columns
4. Partitioning DataFrame by year of cases
5. Save output as csv file
