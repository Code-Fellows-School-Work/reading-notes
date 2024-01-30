# Class 17 - Web Scrapping

## [What is Web Scraping?](https://en.wikipedia.org/wiki/Web_scraping)

- Data scraping for extracting data from websites
- Typically done through automation or a bot as opposed to conducting manually
- Scraped data is typically stored in a database for later analysis
- The process consists of fetching the page then extracting from it
- Commonly used in web mining and data mining

## [Scrape a Dynamic Website with Python](https://scrapingant.com/blog/scrape-dynamic-website-with-python)

- Use the ```BeautifulSoup``` library to extract required content from HTML
- Be mindful on what it scraped because it may scrape the static content instead of the dynamic content if not configured properly
- Use ```Selenium``` or ```Puppeteer``` libraries to execute the JavaScript calls on a dynamic website
- Then web scrape from the dynamically rendered content

## [How to Webscape Without Getting Blocked](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)

- Not all website implement anti-scraping measures, but some do and may block you
- The use of web scraping may increase the demand on the website and it's server which will impact the performance of the website
- Best web scraping practices to avoid being blocked:
    - Check the website's robots.txt file (http://example.com/robots.txt) and look for the words ```User-agent: *``` or ```Disallow:/```. These words indicate the website does not want to be web scraped
    - Make the web scraper more human like by adding delays between scraping and random calls in between web scraping requests
    - Set up a proxy and rotate between as needed 

## [Python Playwrite Tutorial](https://www.youtube.com/watch?v=yp1o9biMMWU)

- Playwrite automates web browsers
    - Ex. automatically logging into your amazon account (as long as 2FA is not used)
- Contains the steps to setup the library and example logic to run the automated process

## Additional Resources

[Xpath Cheatsheet](https://devhints.io/xpath)

[Playwrite Xpath Selectors](https://www.programsbuzz.com/article/playwright-xpath-selectors)

### Questions

1. What are the key differences between scraping static and dynamic websites?

- Scraping from a static website involves extracting data from HTML content and you can use the ```BeautifulSoup``` library to do so. Scraping data from a dynamic website requires events to be triggered to allow for the content to render dynamically. Those events can be automated through ```Selenium``` or ```Puppeteer``` library and then from there, web scraping techniques can be used to scrape the dynamically rendered content.

2. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.

- Check the website's robots.txt file (http://example.com/robots.txt) and look for the words ```User-agent: *``` or ```Disallow:/```. These words indicate the website does not want to be web scraped
- Make the web scraper more human like by adding delays between scraping and random calls in between web scraping requests
- Set up a proxy and rotate between as needed 

3. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.

- Playwrite automates web browsers and it can be helpful in web scraping tasks if the desired web scrape content is behind a login screen or requires a specific path to navigate to. Playwrite can automate the process of login on and replicate the same steps to navigate to the desired web scrape content.
    - Ex. Setting up an automated process of logging onto your ESPN account and extracting news data from a sport's page related to your favorite team

4. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.

- Targets specific elements on a web page for web scraping.
    - Ex. ```//button[text()='Submit']```

## Things I want to know more about

- What are some easy use cases that I can implement web scraping to help automate my life?