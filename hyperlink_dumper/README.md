# Hyperlink dumper
This code dumps hyper links from given link of a web page.


## Features
- scraps Links from given website's link.
- External and internal links both are scrapped.

## Working

- This tool takes webpage URL(You can give multiple also) as input gets the webpage using requests library.
- After that it uses beautiful soup library of Python to saprate all '\<a>' tags
- Results will be saved in hyperlinks.txt

## Things to remember
- It is always advisable to use proxies while scrapping.
- It might get you blacklisted or even banned.
- It might be illegal on some websites.
- Might not be very precise, human interaction needed after completion.


## hyperlink_dumper.py
this code in hyperlink_dumper.py dumps all links regardless external or internal links
removes duplicates from links and saves in hyperlinks.txt file.

## direct_linkmaker.py
Makes direct link from given url.
e.g. some times dumped url is like '/dep/it/' you have to make it like 'https://example.com/dep/it'

## direct_linkmaker_v1.1.py
Saperates links aswell as appnd url and discard any links that are having .pdf or .jpg or .jpeg extension

## Working demo 
![mail_dumper](https://github.com/shyam-chauhan/Offensive_python/assets/59696796/28322ce3-b844-4e33-b61c-ec7bfc98417c)



