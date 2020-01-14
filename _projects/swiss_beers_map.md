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
[BeerAdvocate](https://www.beeradvocate.com/).
The original jupyter notebook can be found
on the [github page](https://github.com/nrbernier/swiss-beer-map).

Note that it is work in progress and there are still a few error
in localizations of the breweries.

{% include_relative swiss-breweries-map.html %}

The size of the markers is proportional to the number of beers
listed on BeerAdvocate,
while the color gives the average ratings of them.

