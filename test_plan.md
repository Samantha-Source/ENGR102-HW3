# Test Plan

1. Create test cases (arrays of numbers and x data point values) in MS Excel.
2. Use built-in Excel formulas to calculate the mu (mean (=AVERAGE)) and sigma(standard deviation of the population (=STDEV.P)) of the arrays.
3. Create a formula in Excel to calculate the Z-score for the data set(=(x - mean)/standard deviation)
4. Create a python tester function which accepts data sets and x values, calls the pre-existing functions to calculate the mu and sigma and runs the completed z_score() function with the resulting data.
4. Copy test data into python.
5. Run tester function and compare outputs to expected outputs on excel sheet.  