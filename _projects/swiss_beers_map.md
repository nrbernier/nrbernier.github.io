---
title: Map of the Swiss breweries
tags:
    - Project
image: 
    path: /assets/photos/speyside.jpg
    thumbnail: /assets/photos/speyside_small.jpg

---
The interactive map below
was obtained by scraping the information of all Swiss breweries
available on 
[RateBeer](https://www.ratebeer.com/).
The original jupyter notebook can be found
on the [github page](https://github.com/nrbernier/swiss-beer-map).


{% include_relative swiss-breweries-map.html %}

The size of the markers is proportional to the number of beers
listed on BeerAdvocate,
while the color gives the average ratings of them.

As a quick summary, 
first a list of 576 Swiss breweries is extracted from
[this RateBeer page](https://www.ratebeer.com/breweries/switzerland/0/191/).
Then the page of each brewery in the list is scraped for 
additional information, such as its address and its list of beers.
The address is turned into longitude and latitude coordinates
using an API of 
[Nominatim](https://nominatim.openstreetmap.org).
Finally, the ratings of all the beers of each brewery is averaged
to create a score for the brewery.




