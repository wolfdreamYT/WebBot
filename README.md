# WebBot

WebBot is a powerfull tool i made that can scan any website and give me all the info/text from it. I used this for news sites since my teacher needed me to find info about different people, but since News stations were always adding so many ads, i decided to make this so i can get all the info i need without needing to ever VISIT the website myself. The program used to respect robots.txt in the version 1.0 but when 2.0 came out i decided to remove it as it was "pointless" for me and my work, infact it got in the way of my work when scanning.

---

## Features

- **Advanced Web Scraping**: Retrieve articles, posts, or other data from websites.
- **Customizable User-Agent**: Rotate user-agents to mimic different browsers.
- **Flexible Output**: Save scraped data in text files and structured formated in another with HTML.
- **Progress Tracking**: Monitor scraping progress with a live progress bar.
- **Multi-Site Support**: Scrape multiple websites with a single configuration.
- **Extensible**: Easily add new scraping rules or parsing logic.
- **No Robots.txt**: Bypasses robots.txt to retrieve info no matter what.

---

## Installation

There are a couple of options when it comes to installing, but here are my favourites:

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/WebBot.git
   cd WebBot

2. **Download & Install**
   1. download the WebBot 1.0 or 2.0, 2.0 is prefered.
   2. install the required libraries (asyncio, aiohttp, hashlib, etc)
   3. open command prompt and navigate to your directory (cd path\to\WebBot\)
   4. open `seeds.txt` and add your URLs you want to extract info from
   5. run `python main.py` and watch the magic happen.
  
     WARNING: This is built for Windows 11 x64, if your using a different OS please update the code to support the architecture of your PC.
