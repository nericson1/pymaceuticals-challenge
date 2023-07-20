# pymaceuticals-challenge
## Adding rows to a DataFrame
I needed to add rows to one of my dataframes in order to have the correct information to create my box plots. I used the link below to figure out I had to use pd.concat in order to add the necessary rows of data.

Link: https://stackoverflow.com/questions/44156051/add-a-series-to-existing-dataframe

## Boxplot formatting
I needed to figure out how to get all 4 boxplots to display on the same figure. I used the link below to figure out how I needed to structure and combine my dataframes in order to get them all displaying in the right place.

Link: https://stackoverflow.com/questions/70927004/plotting-several-boxplots-from-different-dataframes-in-one-graph

## Dictionary keys as labels
I needed to be able to use the keys of my dictionary as the labels for the boxplots since all 4 boxplots are sharing one figure. This resource helped me figure out I needed to use the standard set_xticklabels and pass in dictionary_name.keys() in order to access the necessary information.

Link: https://stackoverflow.com/questions/52273543/creating-multiple-boxplots-on-the-same-graph-from-a-dictionary

## Iterating over rows of a dictionary
I knew there was a way to loop through the rows of a dictionary to collect necessary informatipon, but couldn't remember how to do this or find it in my notes. I found the link below that answered this question, so I used the iterrows() function twice in the creation of my boxplots.

Link: https://www.freecodecamp.org/news/how-to-iterate-over-rows-with-pandas-loop-through-a-dataframe/#:~:text=You%20can%20loop%20through%20rows,dataframe%20and%20access%20its%20values

## Aggregated statistics table
I was able to easily create summary_df using the groupby method to create the dataframe containing the necessary statistics summary, but I did not know how to use the aggregation method for making the second table. I used the link below as a basic structure for writing my code to make this second table.

Link: https://stackoverflow.com/questions/55388610/how-to-calculate-aggregated-summary-statistics-in-pandas-dataframe

## Correlation coefficient
I needed to calculate the correlation coefficient in the correlation and regression section to determine the strength of the relationship between two different factors. I used the link below to determine how to structure my code in order to get the correct value.

Link: https://sparkbyexamples.com/pandas/pandas-correlation-of-columns/?expand_article=1

## Linear regression
I needed to calculate the linear regression model and add it to my scatter plot in the correlation and regression section. I struggled with how to format the code to get the correct values to populate, so I used the link below to figure out exactly what arguments the linregress function takes.

Link: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html
