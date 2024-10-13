# Data Collection of Surnames and First Names from Wikipedia

## Project Description
This project involves the collection of surname and first name data from Wikipedia. The data was gathered using the Python programming language and the Pandas library. 

## Technologies
- **Python**: The programming language used for data collection and processing.
- **Pandas**: A Python library used for data manipulation, which helped manage the tables and data collected.
- **Beautiful Soup**: A library for parsing HTML and XML documents, used to analyze the structure of Wikipedia and extract data.

## Workflow

1. **HTML Analysis**: 
   - Analyzed the HTML structure of Wikipedia pages that contain lists of names. 
   - Identified the relevant elements (such as tables and headers) that contain the required information.

2. **Data Collection**:
   - Used `requests` to download the content of the pages.
   - Employed `Beautiful Soup` to parse the downloaded content and extract the names.

3. **Data Processing**:
   - Transferred the extracted data into a Pandas DataFrame for organization and processing.
 

4. **Data Storage**:
   - Saved the data as CSV files.
## Files
- GivenNames.py and Surnames : The Python scripts containing the code for data collection.
- final_Given_names.csv and finalSurnames: CSV files containing the collected first and surnames names.

## Requirements
- Python 3.x
- pandas
- requests
- beautifulsoup4


