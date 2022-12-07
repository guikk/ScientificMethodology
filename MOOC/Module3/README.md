# MOOC Module 3 Log Journal

# Exercise 03
## Ex. 03-1
> Downloaded the notebook file from Gitlab. Then, replaced the data reading method with the following steps:
> - Check if data file already existed with `os.path.exists()`
> - If not, download from URL using `wget` (Jupyter lets you run linux bash commands using the `!` sign)

## Ex. 03-2
> Edited a copy of the notebook to use the chickenpox data, had some difference in missing data and start year, but overall very similar  data.

In the end I got as a result 2010 being the worst year, different from the MOOC answer (2009). I couldn't figure out why this happened, maybe I didn't fetch the exact same dataset. In the other hand, the best year result was the same.

# PeerAssessment
> I chose to do my analysis with the JHU CoViD-19 cummulative cases dataset.
> Downloading the file from the internet was easy to do and treat for duplication because of the work from exercise 3.1

The first big problem I had was handling the data and R datatypes, it took a little while until I understood how to use the dataframe and found a practical way to plot the data in it. It turned out that it is a lot easier to treat every piece of data (region, observation date) as a column, and the records as rows. In the original document, wach row as a region or subregion and the columns were the different observation dates.

Now the next bump on the road was tuning ggplot, I had myself going back and forth between coloring libraries and scale labels to make the graphs more readable, but after some time I find it went well enough.

> After that, I just had to highlight the biggest takeaways from the graph.

Those were not too hard to point out, from someone who consumed news of this topic throughout all the pandemic.