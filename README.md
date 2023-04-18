## Linkedin CV Generator Documentation

### Introduction
The Linkedin CV Generator is a Python project that generates a Curriculum Vitae (CV) in Microsoft Word (.docx) format by web scraping relevant information from a user's LinkedIn profile. This project uses the following web technologies:

* Selenium WebDriver - to navigate and interact with web pages
* BeautifulSoup - to parse HTML content
* Chrome DevTools Protocol - to retrieve and analyze network traffic

### Requirements
Before you can run this project, make sure you have the following installed:

* Python 3+ - this project was tested on Python 3.9.5
* Selenium WebDriver - the ChromeDriver version used must be compatible with the installed version of Google Chrome. In this project, ChromeDriver version 93.0.4577 was used.
* BeautifulSoup4
* docx

### Installation
- First, clone this repository by running the following command:

`git clone https://github.com/[USERNAME]/[REPO].git`

- Install project dependencies by running the following command:

`pip install selenium beautifulsoup4 docx`

- Download the appropriate version of ChromeDriver that matches the installed version of Google Chrome.

### Usage
* Update the linkedin_login.json file with the user's LinkedIn login credentials.
* Modify the following variables in the linkedin_cv_generator.py as required:
* chrome_path - the path to the installed Google Chrome executable
* driver_path - the path to the installed ChromeDriver executable
* job_search_term - the search term used to find relevant work experience
* Run the linkedin_cv_generator.py file using Python.

### Future Improvements
* Add support for more web browsers.
* Add unit tests to ensure consistent performance.
* Expand functionality to include exporting CV in multiple file formats.
* Issue #1
