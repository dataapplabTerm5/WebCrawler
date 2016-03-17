YelpCrawl: Exhaustive Yelp! Scraper
===================================

Example usage for `yelp`_ extraction.

Extract all restaurant data from a specific zipcode.

::

    $ python2.7 crawler.py -z 98029

    ===== Attempting extraction for zipcode < 98029 >=====
    
    title: Issaquah Coffee Company
    categories: Coffee & Tea
    rating: 4.0 star rating
    ...


Extract all restaurant data from America (all American zipcodes).

::

    $ python2.7 crawler.py

    **We are attempting to extract all zipcodes in Amerrica!**

    ===== Attempting extraction for zipcode < 35004 >=====

    title: Brasher Sam Tire &amp; Auto Service Inc
    categories: Tires
    rating: 5.0 star rating
    ...


Installation:
-------------

::

    $ git clone https://github.com/codelucas/yelpcrawl
    $ cd yelpcrawl
    $ pip install -r requirements.txt

And now you can begin!

::

    $ python2.7 crawler.py -z 98000


