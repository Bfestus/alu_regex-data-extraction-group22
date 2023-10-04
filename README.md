![image](https://github.com/Bfestus/alu_regex-data-extraction-group22/assets/127530529/50f6a501-dad9-444c-9e80-38c3c8151d52)

# Data Extraction Toolkit
## Task Description
The purpose of this toolkit is to facilitate the efficient extraction of diverse data types from messy API responses using regular expressions. Specific patterns have been identified to match and extract the following data categories:

####  Restaurant Data: 
Extract restaurant names and cuisines in the format "Name - Cuisine."

#### Ingredient Lists: 
Extract comma-separated ingredient lists like "ingredient1, ingredient2, ingredient3."

####  RGB Colors: 
Extract RGB colors in the format "rgb(255, 255, 255)" with three numeric values.

####  Social Media Usernames: 
Extract usernames in the format "@username," where the username can consist of letters and numbers.

####  Product Codes: 
Extract product codes in the format "ABC123," where A, B, and C are letters, and 1, 2, and 3 are digits.

####  News Headlines: 
Extract news headlines in the pattern "Headline: Subheader," where both parts are arbitrary strings.

####  Event Dates/Times: 
Extract event dates and times following the pattern "MMM DD, YYYY - hh:mm AM/PM" with standard date and 12-hour time formatting.

####  Email Addresses: 
Extract email addresses in the common format "name@domain.com."

# Implementation
To achieve this task, a Python package has been created, providing essential scripts for data extraction based on the specified patterns. Users can import and utilize these functions according to their data extraction requirements.

Additionally, a user-friendly Command-Line Interface (CLI) program has been developed to simplify the data extraction process. Users can execute the scripts from the command line, specifying the file containing the raw API response data as an argument. The program will then guide the user to select the specific data type for extraction and assist them throughout the extraction process.

This approach ensures that data extraction is not only efficient but also customizable and user-friendly.



