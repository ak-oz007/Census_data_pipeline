# Census_data_pipeline
# HOW THE PIPELINE WORKS?
1. Loading the data from census_data excel to python using Pandas.
2. Applying changes to the column names
3. Handling null values(Transforming and replacing)
4. Saving the transformed data to MongoDB(Atlas DB)
5. Fetching the data from MongoDB and uploading it to MySQLWorkbench schema(Local).
6. Querying the data from SQL to gain insights

# SECURING THE PASSWORDS:
1. Creating a separate Python file to store the credentials used in the python file where we query data.
2. Import the data(String or dict) in the python whenever required to hide the passwords and ports.

