# Module 12 Challenge: Scrape and Analyze Mars Weather Data

This repository contains a README file, an Output folder to store the final results and two python notebooks, namely **part_1_mars_news.ipynb** and **part_2_mars_weather.ipynb**. These notebooks are designed to address the following two deliverables:

### Deliverable 1: Scrape Titles and Preview Text from Mars News

This repository contains code to scrape titles and preview text from Mars news articles. The goal of this project is to extract relevant information from these articles and store them in a Python data structure.

Getting Started:

>Install the necessary libraries: selenium, splinter, beautifulsoup4, and chromedriver.
>
>Use Browser from the splinter library to open a Chrome browser.

Instructions

>Step 1: Visit the Website
>>
>>Visit the Mars news site using the automated browser.
>>
>Step 2: Scrape the Website
>>
>>Create a Beautiful Soup object and use it to extract text elements from the website.
>>
>>Two methods are provided for extracting all the text elements from the website:
>>
>>Find all elements with the class col-md-12 and print the text content of each element.
>>
>>Use the get_text() method from the Beautiful Soup object to extract all text elements.
>>
>Step 3: Store the Results
>>
>>Create an empty list to store the dictionaries containing the title and preview text.
>>
>>Loop through the text elements, extracting the title and preview text from each element.
>>
>>Store each title and preview pair in a dictionary and add the dictionary to the list.
>>
>>Print the list to confirm success.
>>
>>Close the automated browser.

### Deliverable 2: This project involves web scraping data from a Mars temperature data site and analyzing it using Pandas and Matplotlib libraries in Python. The ultimate goal is to answer the following questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
4. Which months have the lowest and the highest atmospheric pressure on Mars?
5. About how many terrestrial (Earth) days exist in a Martian year?

### Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Splinter
- BeautifulSoup

### Steps

1. Visit the website: Use automated browsing to visit the Mars Temperature Data Site.
2. Scrape the table: Create a Beautiful Soup object and use it to scrape the data in the HTML table.
3. Store the data: Assemble the scraped data into a Pandas DataFrame.
4. Prepare data for analysis: Examine and cast the data to the appropriate data types.
5. Analyze the data: Use Pandas functions to answer the five questions.
6. Save the data: Export the DataFrame to a CSV file.

### Results

The results showed that a year on Mars appears to be about 675 Earth days. The third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth. There are 7 Martian months.

### Conclusion

This project successfully scraped data from a website, assembled it into a Pandas DataFrame, and analyzed it using various Pandas functions. The results provided insights into the weather patterns on Mars.

### Contact

If you have any questions or feedback about this script, please feel free to contact me at param.birdi@utoronto.ca.

### Acknowledgments

This code was written by Paramdeep Singh Birdi as part of a project for a data analysis course. Most of the data used in this project was provided by the course instructors.
