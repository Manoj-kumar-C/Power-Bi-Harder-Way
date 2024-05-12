# Import the necessary libraries
import pandas as pd

# Read the data from a CSV file
data = pd.read_csv('data.csv')

# Use the count() function to get the total count of records
total_count = data.count()

# Use the nunique() function to get the count of distinct values
distinct_count = data.nunique()

# Print the results
print("Total count:", total_count)
print("Distinct count:", distinct_count)




Distinct ----> It is used for the just total numbers of records

Count Distinct ---> It gives the count of unique values ---> NOt Duplicates
Count(Distinct)  ---> To initialte ---> Go to fields --> Filter