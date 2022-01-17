# Practice Optimizing DataFrames and Processing in Chunks

### Project completed as part of Dataquest's Data Engineering path.

------

## Introduction
In this project, our goal is to practice with chunked dataframes and optimize a dataframe's memory usage. 

Our data is financial lending data from a marketplace for personal loans that matches borrowers with investors, the [Lending club](https://www.lendingclub.com/). We'll work with a dataset of loans approved from 2007-1011. 

If we read in the entire dataset, it consumes about 67 megabytes of memory. Then, to reach our goal, we will imagine that we only have 10 megabytes of memory available.