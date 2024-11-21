# matplotlib-challenge
fifth week's challenge

Before making any visualizations, I prepared what was given to only show relevant, unique data. For example, I merged the datasets since both of them were relevant; and I removed duplicate rows.

Then, I generated a new dataframe with summary statistics for each drug regimen's recorded tumor volumes --  for easy reference and comparison, I imagine.

The visualizations which begin my Jupyter Notebook are simply visualizations of the data as it is (after being cleaned, of course). There's no manipulation for anybody to find any patterns or anything. Consulting them would be a good way to get to know the data as a whole. They answer the questions: (1) Does every drug regimen have the same amount of timepoints recorded? (No.) And (2) did the data have an equal distribution of female and male mice? (Yes.)

The next visualization to come is a box and whisker, showing medians, IQRs and outliers for 4 drug regimens. It is valuable because their medians and IQRs show which tumor volumes each drug regimen treats and which ones it (or the people carrying out drug regimen's tests) neglects. Outliers show which ranges of tumore volumes need more attention while testing.

The line graph, scatter plot, correlation, and regression focus on mice on Capomulin. Be sure to run the cell for the random mice's line graphs, more than once. There are no two graphs which show any similarities to each other, genuinely. It's a reminder not to call any sweeping generalizations definitive trends.