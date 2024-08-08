# WebScraping/zillow-home-prices

## Overview

This project's purpose is to scrape listing data from houses in the NY area from zillow. 

To scrape another area one can modify the spider script and change the url attribute from the `ZillowSpider` class to that of the area of interest. In the future I would like to either implement a CLI or web interface to search a desired area of interest dynamically rather than changing the script manually. 

## Running the Script

Run the following commands to clone the project and download any nessecary python libraries

```bash
git clone https://github.com/ivokusi/zillow-web-scraper/tree/main
```

Once we've successfully copied the repository, run the following commands

### In Windows

```bash
python -m venv venv
source venv/Scripts/activate
```

```bash
pip install -r requirements.txt
```

### In Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

```bash
pip3 install -r requirements.txt
```

Once we've setup the repository correctly, run the following command

### In Windows

```bash
python main.py
```

### In Mac

```bash
python3 main.py
```
