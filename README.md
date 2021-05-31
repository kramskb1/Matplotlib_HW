I really enjoyed completing this homework assignment. I feel like I am able to use Matplotlib a lot more than I was able to use Matplotlib before completing this assignment. I really enjoyed being able to use various functions in Python to complete this assignment, such as finding outliers, merging data, and creating scatterplots. Using the numpy function in Python was also very helpful in completing this assignment. I ended up importing a lot of functions in Python in the beginning of my code which I believed would be helpful in completing this assignment. I printed the number of mice. I checked for duplicate rows with the same Mouse IDs and timepoints by creating a new dataframe. I dropped the number of rows. I rechecked the number of mice.
I created a summary statistics table of everything that was asked of me by grouping by drug regimen. I generated a bar chart using pandas. I then generated the same bar chart using pyplot. Next, I created a pie chart using pandas to show the distribution of female versus male mice.  I then calculated the quartiles, calculated the interquartile range, and looked for outliers. I calculated the lower bound by subtracting 1.5 times the interquartile range from Q1. I calculated the upper bound by adding 1.5 times the interquartile range to Q3. I calculated where potential outliers for each treatment regimen would lie. I made sure to incorporate the greatest timepoint for each mouse in my code. I generated a box plot of the final tumor volume of each mouse across four regimens of interest. I can clearly see that there is an outlier for infubinol in the data.
I then generated a line plot of tumor volume versus time point for a single mouse treated with capomulin. I can clearly see the impact that capomulin has on the size of the tumor volume by the line plot. I then generated a scatter plot of average tumor volume versus mouse weight for all of the mice in the capomulin regimen. I can clearly see from the scatter plot that if a mouse weighs more, the overall trend is that he will have a larger tumor volume. 
I then calculated the correlation coefficient by using the st.pearsonr function that I found on Google when I searched for how to obtain correlation coefficient. The correlation coefficient for mouse weight and tumor volume for the capomulin regimen that I found is 0.84. That is a pretty high correlation coefficient, and shows that the larger a mouse weighs, the more tumor volume the mouse has in general. 
In order to plot the linear regression, I found several Python tools that would be helpful on Google. I found the linregress function, how to create regress values, and how to create a regression line equation.  I initially did not come up with an accurate regression line because I did not realize that the syntax that I found on Google for when I was using the linregress function, which told me to input slope, intercept, rvalue, pvalue, and stderr (standard error), had to be inputted in that specific order. I eventually figured that out when seeing that my regression line did not match the data unless I did that. 
I plotted my x axis and y axis for 2 integers higher and 2 integers lower than the minimum of my x values and minimum of my y values so that the regression line along with my data points can be clearly seen. The regression line matches the expectation from looking at the correlation coefficient, as it shows a pretty big correlation between the weight of the mouse and the size of the tumor volume that the mouse has. I really enjoyed completing this assignment. It opened my eyes to how much can be done with the Matplotlib function in Python and proved to me again how many different types of data can be analyzed in a lot of different ways using Python. 
