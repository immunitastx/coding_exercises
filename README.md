# Overview

Here, we provide a toy "omics" dataset consisting of data resulting from some hypothetical single-cell genomics assay. The data was generated from a simulation, so it is not real. This dataset consists of 1,000 cells and 500 assayed genes. These cells come from two hypothetical experimental conditions: "condition_1" and "condition_2". The task here is to identify genes whose mean values differ between these two conditions.

# Data

The dataset consists of two files:
* `omics.tsv.gz` is a compressed TSV file storing the 1000 x 500 data values for the 500 genes in 1000 cells.
* `condition.tsv.gz` is a compressed TSV file storing which condition each cell belongs to

# Task

Write an analysis in either a Jupyter notebook or RMarkdown notebook, using either Python or R, that analyzes this toy dataset in order to find genes that differ between the two conditions. At the end of your notebook, you should list the genes that are different between the two conditions. You can use whatever methods you would like to accomplish this task! We encourage you to perform exploratory data analysis to show us how you approach a new dataset. 

You can treat the data values as normally-distributed within each condition (such as normalized gene expression values). Furthermore, some of the values may be negative.

Note, the signal in this data is strong! The genes that are different between the two conditions are _very_ different, so many methods may work just fine! We are looking to see how you approach this problem. What method(s) did you employ? How did you structure your code? What plots did you make?

# Time to completion

This task should take anywhere from 20 minutes to 1 hour to complete. If you reach the one hour mark, please reach out to us so that we can talk through what you are doing and any issue you may be stuck on! 
