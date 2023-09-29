# DataAnalysisExample
DataAnalysisExample-(SCALA)
Setting Up the Code:

The code is contained within an object called AdvancedDataAnalysis. This object includes functions necessary for data analysis.
Reading Data from a CSV File:

The function readDataFromCSV("data.csv") reads data from the "data.csv" file and returns it as a List[Double].
Filtering Outliers:

The function filterOutliers(data: List[Double]): List[Double] filters out the outliers from the data. Using the mean and standard deviation, values that are 2 standard deviations away from the mean are filtered out.
Calculating the Mean:

The function calculateMean(data: List[Double]): Double calculates the mean of the dataset.
Calculating the Variance:

The function calculateVariance(data: List[Double], mean: Double): Double calculates the variance of the dataset.
Calculating the Standard Deviation:

The function calculateStandardDeviation(variance: Double): Double calculates the standard deviation of the dataset.
Data Analysis and Reporting:

The main function conducts data analysis using the above functions. It reads the data, filters out outliers, then calculates the mean, variance, and standard deviation. The results are printed to the console.
To use the code:

Prepare the Scala Environment: Firstly, you need to set up a Scala development environment. You can use advanced Scala IDEs like IntelliJ IDEA, Eclipse, or Visual Studio Code.

Prepare the CSV File: The code reads data from the "data.csv" file. Create this file and populate it with the required data.

Run the Code: Run this Scala file either in your Scala IDE or from the terminal. For example, you can run it in the terminal using the command scala AdvancedDataAnalysis.scala.

Examine the Results: The code prints the filtered data set, mean, variance, and standard deviation values to the console, allowing you to examine the results of the data analysis.
