# Prajavani Newspaper Scraper
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
<br/>This is a python project which enables a user to scrape newspapers from [Prajavani](http://epaper.prajavani.net). It supports Chromium based Edge and Chrome.
This project has multiple modules written in Python which can be used for different purposes.
## Setup
### Requirements
1. [Python interpreter](https://www.ics.uci.edu/~pattis/common/handouts/pythoneclipsejava/python.html) (The latest version at the time of writing this is 3.8.3. But the installation instructions are the same.)
2. [Chromium based Edge browser](https://www.microsoft.com/en-us/edge) or [Google Chrome](https://www.google.com/intl/en_in/chrome/)
3. [WebDriver for Edge](https://msedgewebdriverstorage.z22.web.core.windows.net/) or [WebDriver for Chrome](https://chromedriver.storage.googleapis.com/index.html)
4. Additional modules required
   1. selenium
   2. requests
   3. PyPDF2
   4. natsort
   
   To install these, run `pip install requirements.txt` in the command prompt.
#### Webdriver Installation
1. Download the WebDriver from the link. The version you would want to download is the version of your Edge browser. To check your version, type `edge://version/` or `chrome://version/` in the address bar.
<br/><br/>![About version](../assets/newspaper-scraper/edge-webdriver-download-delay-10ms.gif)
![Download dialog](../assets/newspaper-scraper/download-dialog.png)
2. In the zip, there will be a `msedgedriver.exe` file.`chromedriver.exe` for Chrome.<br/><br/>![zip folder](../assets/newspaper-scraper/zip-folder.png)
3. Extract this to the folder of your choice.
4. Go to `prajavani-dl-edge.py` and replace `path/to/webdriver` with the path your `msedgedriver.exe` is located in. Or, go to `prajavani-dl-chrome.py` and do the same.<br/><br/>![Webdriver-path-change](../assets/newspaper-scraper/change-webdriver-location-small.gif) 