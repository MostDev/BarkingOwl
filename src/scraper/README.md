####Scraper####

This tool pulls a list of urls and phrases from the database, and spits out processed pdf docs.


#####Files#####


    pdfimp.py - this scraper will locate all of the PDF's on a website and return a list of their URLs

    dler.py - this file downloads all of the links it gets from pdfimp

    unpdfer.py - this will pre-process and then pdf->text a downloaded pdf

    scrapper.py - this file takes in a url, and spits out processed pdfs

    runscrapper.py - this is the entry point, and interfaces to the database and scrapper.py


#####Dependancies#####

    > pip install pdfminer
    
    > pip install BeautifulSoup4

    > pip install nltk

    > pip install python-mysql

    > pip install python-magic

