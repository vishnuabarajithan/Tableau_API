## Tableau Online Data Export
This Python script utilizes the Tableau Server Client library (tableau_api_lib) to connect to Tableau Online and export data from a specific view on a dashboard. The exported data is then saved to a CSV file.

# Connection Setup:

The script establishes a connection to Tableau Online using the provided configuration, including server details and personal access token.

# Retrieve Views Information:

Fetches information about all views from the Tableau Online server and converts it into a pandas DataFrame.

# Filtering Views:

Filters the DataFrame to get information about a specific workbook ('WORKBOOK_NAME').

# Export Data from a View:

Utilizes the specified view ID ('VIEW_ID') to extract data from the corresponding view on the dashboard.

# Save Data to CSV:

Saves the extracted data to a CSV file named 'file_name.csv' in the specified path ('/PATH/').

# Connection Cleanup:

Signs out and closes the connection to Tableau Online.
