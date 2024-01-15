# AutomateYourJobSearch
- Automating the entire job application process on the Carleton Co-Op portal with Python and the Selenium web driver

- automatedJobMatcing.py  is a python script to find all revelent jobs on the Carleton Co-Op portal with selenium, and then extract the data to a txt file name IDed from job position for later use.

This project leverages the power of Selenium to automate the process of job matching for co-op opportunities. The script logs into a university portal, navigates through all job postings, and extracts job postings data from listings matching a predefined criteria. It then saves the job descriptions to individual text files for further analysis or customization.

variables to customize:
- regexPattern
- MyUsername (.env)
- MyPassword (.env)

Features:
- Automated login to university portal
- Navigation through co-op job pages
- Extraction of job information based on specified criteria, currently using regex but many alternative methods avalible
- Storage of relevant job information in text files

Dependencies:
  - Python
  - Selenium
  - WebDriver (Chrome)
  - dotenv
  

Usage:
  - Set up a virtual environment and install dependencies from requirements.txt.
  - make sure to activate the virtual environment
  - Create a .env file with your login credentials.
  - Run the script to automate the job matching process.

how to setup venv:
- python -m venv venv               # or python3, depending on your setup
- python -m venv venv               # or python3, depending on your setup
- venv/bin/activate                 # or activate.bat on Windows
- pip install -r requirements.txt 
- #should be good to run now with: python -u filename.py


More requirerements:
  - global variables that need customization are at the top of the file
  - please enter your login credentionals into a dont env file with approriate varibles before running
  - regexPatter is a gloabal variable that will be used to file matching jobs


Note:
  - global variables that need customization are at the top of the file
  - Make sure to customize the criteria(REGEX) in the script to match your job preferences.
  - Job position name for files is changed to replace invalid characters 

Contributing:
Contributions are more that welcome! Feel free to open issues, submit pull requests, or suggest enhancements to make this tool more effective and user-friendly.
  -neccasary improvements:
    - fix jobs page navigation to scrapper each page (currently only does first 100 listing on page 1 of job board)
    - 


