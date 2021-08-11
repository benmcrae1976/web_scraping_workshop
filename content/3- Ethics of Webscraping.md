---
title: Ethics of Webscraping
nav: Content
topics: ethical considerations, permissions, scraping potentially sensitive data
description: >
    This section covers the ethical and regulatory guidelins for webscraping for research.   
---

## Getting started  

Scraping the web for data is

excellent for publically available content - 
probelmatic where there are people involved - privacy issues - 
not so cool to try and scrape data from behind a paywall and so on

examples of webscraping gone bad - 





## Ethical consderations

Befor scraping-
is the data feely publically available

what are the permissions as set by the page owners (robots.txt)

are there people involved?  could their identity or privacy be compromised?

API?
written permissions



`workshop-template-b` contains a series of [Liquid "includes"](https://jekyllrb.com/docs/includes/) to add basic [Bootstrap components](https://getbootstrap.com/docs/4.1/components/) to your Markdown content.
Examples below demonstrate the includes.

--------

## good practice/bad practice

https://www.empiricaldata.org/dataladyblog/a-guide-to-ethical-web-scraping - direct quote at present

THE API WAY IS OFTEN THE BEST WAY
Some websites have their own APIs built specifically for you to gather data without having to scrape it. This means that you’d be doing it according to their rules; you have been authorized to get the information. So, if there’s an API, use it instead of scraping.

RESPECT THE ROBOTS.TXT
Also known as Robots Exclusion Standard, the robots.txt file is what indicates the web-crawling software where it is allowed (or not allowed) within the website. This is part of the Robots Exclusion Protocol (REP) which are a group of web standards created as a way to regulate how robots crawl the web.

READ THE TERMS AND CONDITIONS
This is the main way the website owner tells you the rules. Yes, it’s easier to just click “I agree” or “I accept” and hope for the best. Remember they wrote those for a reason. They are talking to you, listen to what they have to say.

BE GENTLE
The process of scraping can be pretty harsh on the server, and aggressive scraping can sometimes lead to functionality issues, generating a bad user experience for human users. So, make a habit to do the scraping off-peak hours. And don’t forget to space out the requests so the website’s owner won’t confuse your scraping for a DDoS attack.

IDENTIFY YOURSELF
The website’s administrator may notice some unusual traffic happening. Manners come first, so let them know who you are, your intentions, and how to contact you for more questions. You can do this by simply adding a User-Agent string with your information, so they will be able to see it. Is that simple.

ASK FOR PERMISSION
Some basic human courtesy is always appreciated. They have something that you want, be courteous and ask before assuming the information is free for you to take. Remember: the data doesn’t belong to you.


VALUE THE CONTENT YOU KEEP
You should only take the kind of content that you need. And always have a good reason for getting the content in the first place. The purpose of using the data is to create more value, not duplicate it. 

TREAT THE DATA WITH RESPECT 
You were given permission to take the content, but that doesn’t mean you can now grant that permission to others. Don’t pass it off as if it were your own. 

GIVE BACK WHEN YOU CAN
Look forward to giving back to the owner. Give them credit in an article or in social media, and try to drive some good traffic back to their website.

PRACTICE ETHICAL WEB SCRAPING
The need for data sources increases over time and many websites don’t have their own APIs for developers to access the data they want. This only means that web scraping practices will just grow over time and it is important for developers to know how to do it right.

As you can see, it is a matter of respect, good manners, and proper human relationships to keep your web scraping healthy and ethical.
----------

#### share credit dont harrass
from https://monashdatafluency.github.io/python-web-scraping/section-5-legal-and-ethical-considerations/ 
Share what you can. If the data you scraped is in the public domain or you got permission to share it, then put it out there for other people to reuse it (e.g. on datahub.io). If you wrote a web scraper to access it, share its code (e.g. on GitHub) so that others can benefit from it.

Don't break the Internet. Not all web sites are designed to withstand thousands of requests per second. If you are writing a recursive scraper (i.e. that follows hyperlinks), test it on a smaller dataset first to make sure it does what it is supposed to do. Adjust the settings of your scraper to allow for a delay between requests. By default, Scrapy uses conservative settings that should minimize this risk.

Publish your own data in a reusable way. Don’t force others to write their own scrapers to get at your data. Use open and software-agnostic formats (e.g. JSON, XML), provide metadata (data about your data: where it came from, what it represents, how to use it, etc.) and make sure it can be indexed by search engines so that people can find it.

---------


#### Modal

`{% raw %}{% include modal.html button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}{% endraw %}`

{% include modal.html button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}

-------------

#### YouTube embed

`{% raw %}{% include video-embed.html youtubeid="moJgWrD6dwg" caption="Example video" %}{% endraw %}`

{% include video-embed.html youtubeid="moJgWrD6dwg" caption="Example video" %}
