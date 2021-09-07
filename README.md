# Mining "No Green Pass Docenti" Data  💉 😷 :it:

![Firmatari](assets/firmatari.png)

Visualising regional data and other analyses from the "No Green Pass Docenti" website data.

This repo is basically me playing around with HTML scraping and map visualisation. The analyses from the codebase in this repo are not meant to offend anyone. All the information visualised and used for the analyses are of public domain and available at the webpages under [the data sources section](#data-sources) of this markdown file.

<!-- Thanks to [@UmarSpa](https://github.com/UmarSpa), [@rockNroll87q](https://github.com/rockNroll87q) everyone who contributed with advice, pointers, or simply by being bothered by a really excited me while writing the code in this repo. --> 

The example notebook is available here 👉 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/denbonte/rogue-yoda/blob/main/map_nogp.ipynb)

## To-Dos

- [x] scrape data from the no-gp webpage
- [x] save into a Pandas DataFrame
- [x] rough (manual) mapping between uni and region
- [x] plot on the regional map
- [ ] break down per role/other analyses
- [ ] plot dinamically updating map in an interactive HTML fashion

## Data Sources

* No green pass signatures Data from: [nogreenpassdocenti.wordpress](https://nogreenpassdocenti.wordpress.com/s/)

* Data on Italian eniversities employees from: [USTAT MIUR (2019)](http://ustat.miur.it/dati/didattica/italia/atenei#tabriepilogo)

* Data on Italian population per region from: [Tuttitalia.it - ISTAT (2021)](https://www.tuttitalia.it/regioni/popolazione/)

* Map data on Italian regions: [sramazzina/italian-maps-shapefiles](https://github.com/sramazzina/italian-maps-shapefiles)
