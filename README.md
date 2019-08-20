I have done this exercise to understand :<br />
- process to use custom visualization in PowerBI desktop<br />
- correlation Analysis of data features<br />

For this I have referred Mr. Siddharth Mehta's article posted on https://www.mssqltips.com<br />
Link for the article is mentioned at the end of readme file.

## Correlation Analysis & Matrix :<br />
Correlation Analysis is a fundamental method of **Exploratory Data Analysis** to find a relationship between different features in a dataset. The degree to which one variable moves in relation to the other is measured by the **correlation coefficient "r"**, which quantifies the strength of the correlation between two variables.<br />

Correlation co-efficient typically referred as Pearson’s co-efficient always ranges between -1 to +1.<br />
For example, If feature X and feature Y have a :<br />
1. Correlation coefficient of -0.1 indicates weak negative correlation<br />
2. Correlation coefficient of -0.9 indicates a strong negative correlation<br />
3. Correlation coefficient of +0.8 indicates a strong positive correlation<br />

#### Types of Correlations :
1. Negative correlation or Inverse correlation is a relationship between two variables whereby they move in opposite directions. Here, correlation coefficient value will be closer to -1.<br />
2. Correlation coefficient of Zero is an indication that two variables are uncorrelated and move independently of each other.<br />
3. Positive correlation is a relationship between two variables in which both variables move in tandem—that is, in the same direction. Here, Correlation coefficient value will be closer to +1.<br />

=> The square of this figure **"R-squared"** indicates the degree to which variation in one variable is related to the other.

## Custom Visualization in PowerBI :<br />

**(1)** Download the correlation plot visualization from Microsoft Appsource<br />
https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104380814?src=office&tab=Overview<br />

For download,  You will need a Work or school Microsoft account.<br />

Plus, This custom visualization is having R package dependencies.<br />
So, To use this visual, you must install R on your local computer.<br />

Image **PowerBI Error for R Installation.JPEG** shows PowerBI popup if No R Installation is found on your system.<br />

**(2)** Sample dataset represents Car Performance Metrics like miles per gallon, horsepower, transmission, acceleration, cylinder, displacement, weight, gears, etc.<br />

**(3)** **CustomVisualization_PBIX.pbix** - my powerBI file. Both components mentioned in point1 (correlation plot visualization and R Installation), will be required to see this file. 

**(4)** **Corr Matrix of Car Performance Matrix.jpeg** is screenshot of correlation matrix I have prepared.

Please refer following link for detailed information.<br />
https://www.mssqltips.com/sqlservertip/5197/correlation-analysis-using-correlation-plot-in-power-bi-desktop/<br />

Thanks,<br />
Kunjan Shah.





