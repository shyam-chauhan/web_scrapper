# Email scapper/dumper
 
Tool to scrap E-mails from a website's link.

## features
- scraps E-mails from given link.
- change REGEX to target different information like phone number.
- While it is very hard to search for Emails manually on websites, this can make it easy.
- find Emails that are not visible e.g. given in matatag or hidden tags etc.
- Agent is used to make request look legimate.

## working

- This tool takes webpage URL(You can give multiple also) as input gets the webpage using requests library.
- After that it uses regular Expressions(REGEX) to find all email addresses using specified pattern and displays it on terminal.
- The regex pattern that I have used is : "[a-zA-Z0-9-_.]+@[a-zA-Z0-9_]+[.][a-zA-Z.]+"

## things to remember
- It is always advisable to use proxies while scrapping.
- It might get you blacklisted or even banned.
- It might be illegal on some websites.


# version 1.1

Dumps all E-mails from given links from a text file and writes output to mails.txt file


# version 1.2

Modified code to search for specific keyword and dump that data only.


![mail_dumper](https://github.com/shyam-chauhan/Offensive_python/assets/59696796/28322ce3-b844-4e33-b61c-ec7bfc98417c)
