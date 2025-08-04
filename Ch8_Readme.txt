Challlenge 8: List Locally

1. Instructions:
Please ensure that the files Challenge_8_Engine.ipynb and Openstates_API_Autocaller.ipynb are in the same folder. Additionally, ensure that a folder named 'data' is in the same working directory, as this is where the data files will output to. These files are stored as json file type due to the presence of commas within the retrieved columns from openstates that break the excel/csv format. Please use a third party program such as dataiku to read these in and combine into one datafile.

Openstates_API_Autocaller.ipynb: This is the main file that the user will run. Open this file and insert your API key retrieved by making an account at https://openstates.org. All instructions on parameters and function details are contained within this jupyter notebook.

Challenge_8_Engine.ipynb: For details about the inner workings of the api call as well as making future modificiations, please open the engine file: Challenge_8_Engine.ipynb and refer to the get_legislation_data function. This is the main calling function that the file uses to retrieve data from openstates. In it, you can modify the call to pertain to a specific legislator or session.

2. Program Limits Note: 
The current limits of the program are described within the main file. Please read and understand that a free license apikey is limited. Additionally, many states do not populate their bill subject information. In these cases, the api autocaller will not break but will keep moving on to the next set of 10 pages until the apikey uses for the day are exceeded. This will also print to console when this point has been reached.

