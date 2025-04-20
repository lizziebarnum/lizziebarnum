# CIS4340 HW03 Project Summary

## Scraper Choice
I chose to use BeautifulSoup as my scraping tool. I selected it over Scrapy because it offers more flexibility for projects that require highly customized parsing logic. Since my goal was to extract structured data from a single Wikipedia page with multiple irregular HTML tables, where I'd have to reformat some data and calculate columns, BeautifulSoup provided the direct access I needed to manipulate the tags and handle the inconsistencies between tables.

I used requests to retrieve the page and BeautifulSoup to parse the HTML content. Overall, it took about an hour to set up the initial extraction logic and another few hours to get the data in the precise format I needed.

## Prompts Used

## Strategy Employed

## Python Development Tools Used
I developed this project using Visual Studio Code (VS Code) as my primary IDE. I used the built-in terminal in VS Code for testing the script, and I added logging and exception handling to make debugging easier. For quick CSV previews, I redirected the script output to files.

## Plan for Developing Functions

## Difficulties
I faced a number of difficulties while conducting this project:
- Setting up BeautifulSoup. I had never used this tool before so it took me a while to get used to it.
- Dealing with different formats. It took me a long time to figure out how I could parse different tables that had different columns and didn't line up exactly.
