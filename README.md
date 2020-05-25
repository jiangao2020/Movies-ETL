# Movies-ETL
## Assumptions
After the Wikipedia data and Kaggle are cleaned up and in tabular formats, we merged them by IMDb ID and use the Kaggle data as the precedent data becase it is more consistent. 

We fill in zeros and missing data by subsitituting data from Wikipiedia.

We replace values by converting columns to new data types.

The majority two forms of the box office data and budget data are $xxx.x million (or billion) and $xxx,xxx,xxx, we can use these to parse the values.
  
The patterns hour + minute and minute are used to parse the running time.

The adult column is dropped because the majority of the output is False, which is a bad data to the whole analysis.
