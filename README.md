# Legitimate_Interest_Crawler
This is a web crawler for scraping privacy notices from the 10,000 most popular websites according to the Tranco website ranking.


# Setting up the repo
0. Install Google Chrome package
1.  * `brew install google-chrome`
2. Clone this repository in the remote machine
3. To use this code, you will need to have Python 3 installed on your machine.
  You can download it from the official [Python website.](https://www.python.org/downloads/)
3. Navigate to the Code Directory
   * `cd code`
4. Create a new environment:
    - can be done with conda or virtualenv
5. Activate the new environment and install the requirements:
    - activate the environment
   * `pip install -r requirements.txt`
6. You should now be able to run the code as follows:
   * `python crawler.py` 
   

# Results
The code will output a table with the following information for each website in the input file:
    [Rank,
    Website URL,
    Number of pages crawled,
    Whether there are any legitimate interests on the website,
    Number of clicks needed to find legitimate interests (if any),
    Error (if any)]
The code will also output a CSV file with the list of websites and their legitimate  purposes(in terms of True or False).

Additionally, Screenshots and text data are saved in output_files/

# Contributing
If you would like to contribute to this project, please open an issue or submit a pull request on GitHub.

# Disclaimer
The web crawler is from May 2022 and relies on specific website design features to correctly identify and locate privacy consent notices. The design of many websites changes over time, however. If you wish to reuse the crawler, you will mostl likely need to update the code.
