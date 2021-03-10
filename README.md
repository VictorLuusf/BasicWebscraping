  <h3 align="center">Basic Webscraping</h3> 
  
  <!-- ABOUT THE PROJECT -->
## About The Project
The following project is that demonstrates a few different ways to perform Webscraping.

### Prerequisites

Make sure you have these packages installed below. You will need to run these in terminal if you are on Mac or commpand prompt if you are on Windows.

*pip install requests
```sh
pip install requests
```

*pip install beautifulsoup4
```sh
pip install beautifulsoup4
```

Some knowledge of For Loops
```sh
https://docs.python.org/3/tutorial/controlflow.html
```

### Installation
You will need Jupyter Notebook or any programming environment you prefer. I recommend Juypter Notebook. It is what I used to perform webscrapping.
```sh
https://jupyter.org/
```
You can always download anaconda. It is free platform and includes juypter notebook.

```sh
https://www.anaconda.com/
```

<!-- USAGE EXAMPLES -->
## Usage
You can use these Juypter Notebooks to teach yourself how to perform webscraping and experiment on scraping other data from websites on your own.

Quick Tutorial:
Go to http://quotes.toscrape.com/ to practice scrapping quotes

You will want to hover your mouse over the element you are trying to scrape. In this example you will want to hover your mouse over the quote then right click it and click on inspect.

![alt text](https://github.com/VictorLuusf/Webscrapping/blob/main/Images/Inspecting%20the%20HTML%20Code.png)

In this instance the element is a 'span'. The class is a 'text'

![alt text](https://github.com/VictorLuusf/Webscrapping/blob/main/Images/Finding%20Your%20Quotes.png)

Then in the code, you will want to use BeautifulSoup's soup.find_all. Below is some sample code of how I put this together.

![alt text](https://github.com/VictorLuusf/Webscrapping/blob/main/Images/Sample%20Code.PNG)

## Future Versions
I plan to work on a new version of this webscraper to include moving this data into a Database. I'm also planning on demonstrating turning that data into a data frame with pandas and performing some analysis. I might even turn it into a separate project. If I do, I will provide a link to it here.
