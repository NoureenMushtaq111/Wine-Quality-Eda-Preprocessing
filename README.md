This project looks at a white wine dataset to find out which chemical ingredients make a wine get a higher quality rating.
The Data Before & After: * Started with a raw file of $1,599$ rows that had broken header lines.
After cleaning, fixing the headers, and removing exact duplicates, the final clean dataset has exactly $1,359$ unique wine samples and $12$ different columns.
Cleaning Results: * $0$ missing or null values were found
Checked for highly repetitive features using a threshold of $r > 0.90$, but no columns were dropped because all variables were uniquely independent.
The Key Discoveries (Results):Alcohol content has the strongest positive impact ($\approx +0.48$ correlation). Wines with higher alcohol percentages consistently get higher quality scores.Volatile acidity has the strongest negative impact ($\approx -0.40$ correlation). High volatile acidity gives wine an unpleasant vinegar taste, which severely lowers expert ratings.Sulphates ($\approx +0.25$) and Citric Acid ($\approx +0.23$) also show minor positive links to better quality.
How to use it: Install pandas, numpy, seaborn, and scipy, then run the Wine dataset .ipynb notebook to see the generated distribution graphs and the detailed correlation heatmap.
