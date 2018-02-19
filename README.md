# Data

**Author:** Diego A. Guerrero

**Last Edit:** 02/19/2018.

**NOTICE:** Content is freely available. All datasets are original content from ongoing projects. Please quote if used.


## Venezuelan Liquor Prices

File: price_index.csv

![02-19-2018](https://raw.githubusercontent.com/guerreroda/data/master/cpi.png)

### Methodology.
- An online Venezuelan liquor store is scraped daily for all its products and prices since July 2017. Week 2017-09-10 is missing for all values.
- The dataset comprises a panel with i=3,411 and t=135 which is later resampled in weekly frequency using the last available value.
- From all products, 574 items have less than 2 missing value. 11 of those are selected as a bundle.
- The following (arbitrary) weights were applied to construct a CPI:

-- *low cost liquor 80%:* 'cerveza-tovar-pilsen', 'vodka-bajo-cero', 'ron-cacique', 'ron-angostura'
-- *mid cost 15%:* 'ron-cacique-500-anos', 'ron-santa-teresa-1796', 'vino-la-huerta-merlot', 'vino-santa-carolina-cabernet'
-- *high cost 5%:* 'whisky-black-label-media-botella-media-botella', 'whisky-chivas-regal-12-anos', 'ron-cacique-antiguo'

Resulting data is uploaded as price_index.csv
