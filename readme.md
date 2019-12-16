# Robot Test 1

## Usage

Simple usage:

`robot --outputdir <Output directory> <Tests directory>`

Example:

`robot --outputdir results tests`

## Setup

### 1. Install Python

This is supposed to work with version 2 or 3 of [Python](https://www.python.org/downloads/)

### 2. Install Robot Framework

`pip` should be installed along with Python. You can install [Robot Framework](https://robotframework.org/#introduction) and the [SeleniumLibrary](https://github.com/robotframework/SeleniumLibrary/#introduction) like so:

```
pip install robotframework
pip install --upgrade robotframework-seleniumlibrary
```

### 3. Install browser driver

Selenium requires a browser driver in order to automate interaction. This can be installed in two ways:

1. Download the right driver (like `chromedriver`) from the [Selenium Client Driver](https://selenium.dev/selenium/docs/api/py/index.html#drivers) page
1. Use a tool called [WebDriverManager](https://github.com/rasjani/webdrivermanager) to download and install it. Example:   
```
pip install webdrivermanager
webdrivermanager firefox chrome --linkpath /usr/local/bin
```
