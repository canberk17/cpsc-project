# cpsc-project


It is the data of concentration of Carbondioxide between 1958 and 2015 data is shown in the form of integers

The"average"column contains the monthly mean CO2 mole fraction determined from daily averages. The mole fraction of CO2, expressed as parts per million(ppm) is the number of molecules of CO2 in every one million molecules of dried air(watervaporremoved).

To determine the "trend" value for each month by removing the seasonal cycle; this result is shown in the "trend" column.Trend values are linearly interpolated for missing months. The interpolated monthly mean is then the sum of the average seasonal cycle value and the trend value for the missing month.

To display my data I can either use a line chart, histogram, or a bar chart

I will present how much the mean concentration of CO2 has increased over the years with the python library seaborn/or matplotlib, and use a line chart.

Therefore I will be focusing on the 'date' and the 'average' where date will be presented on the x-axis and the average on the y-axis.


Furhtermore, I will try to visualize the predictions for the mean concentration in the upcoming years based on the data. Therefore I can use other parameters in my data instead of only the 'date' to see if there is a correlation between the other parameters and the increase in the mean concentration of CO2.

Therefore I can inniate other libraries (sckit-learn) to use in my helper functions to run a feature importance test,a regression test, and visualize the results which I will add to my analyze function


I will use the 'average' and 'date' column to present how much the mean concentration of CO2 has increased over the years
