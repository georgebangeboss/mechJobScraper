# Job web scraper

Scrapes the web for recently posted mechanical engineering jobs in Kenya
## Installation Guide

1. Make sure python 3.9 or higher is installed in your machine
2. Create virtual environment

    ```python3 -m venv venv```
    
3. Check [here](https://docs.python.org/3/library/venv.html) for more info on python virtual environments. Activate virtual environment with following commands. 

    ```source venv/bin/activate``` for Linux distros
    
    and
    
    ```venv\Scripts\activate.bat``` for Windows cmd
 
4. Install required dependencies (BeautifulSoup, lxml, requests) from requirements.txt file using the command 

    ```pip install -r requirements.txt```

5.  Run the command below in your terminal to get top job suggestions.Internet connection required

    ```python main.py```
