# Chicago Election Results Map
An interactive map of past Chicago election results built with Leaflet and D3.

[View the map here.](https://sabrinadchan.github.io/chi-election-results-map/)

## Data
The map currently displays election results from all non-judicial races, including ballot referenda, overlapping with the City of Chicago from every Democratic primary, general, and runoff election between 2015 and 2020. For races extending outside of Chicago, only results within Cook County are included.

Chicago election results were scraped from the [Chicago Board of Election Commissioner's website](https://chicagoelections.gov/en/election-results.html) and cleaned using this [Python script](https://github.com/sabrinadchan/chicago-elections-scraper). Suburban election results were scrapped from the [Cook County Clerk's website](https://www.cookcountyclerkil.gov/election-results).

## To Do
* Integrate demographic and socioeconomic data from the U.S. Census Bureau to the geospatial data and allow filtering the precincts by the Census data.
* Add results from 2016, 2018, and 2020 judicial elections.
* Display the breakdown between Cook County and Chicago vote totals for relevant elections.
* Display the correct number of winners in MWRD and Democratic National Convention Delegate Races.
* Allow users to investigate estimated election results for a particular aggregated by another district (e.g. Presidential primary results by state house district or IL-4 by Chicago ward)