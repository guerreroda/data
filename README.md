# Data

**Author:** Diego A. Guerrero

**Last Edit:** 02/19/2018.

**NOTICE:** All datasets are original content from ongoing projects available for free. Please make good use of it and quote.


## Venezuelan Liquor Prices

File: price_index.csv

![02-19-2018](https://raw.githubusercontent.com/guerreroda/data/master/price_index.png)

### Methodology.
- An online Venezuelan liquor store is scraped daily for all its products and prices since July 2017. Week 2017-09-10 is missing for all values.
- The dataset comprises a panel with i=3,411 and t=135 which is later resampled in weekly frequency using the last available value.
- From all products, 574 items have less than 2 missing value. 11 of those are selected as a bundle.
- The following (arbitrary) weights were applied to construct a CPI:

| Low Price (80%)  | Mid. Price (15%) | High Price (5%) |
| ---------------- | ---------------- | --------------- |
| 'cerveza-tovar-pilsen'  | 'ron-cacique-500-anos'  | 'whisky-black-label-media-botella-media-botella' |
| 'vodka-bajo-cero' | 'ron-santa-teresa-1796'  | whisky-chivas-regal-12-anos' |
| 'ron-cacique' | 'vino-la-huerta-merlot'  | 'ron-cacique-antiguo' |
| 'ron-angostura' | 'vino-santa-carolina-cabernet'  | |


Resulting data is uploaded as price_index.csv

| Date | Index | Inf. |
| ---- | ----- | ---- |
| Jul-17 | 100.00 | NaN |
| Aug-17 | 142.37 | 42% |
| Sep-17 | 223.13 |	57% |
| Oct-17 | 471.30 | 111% |
| Nov-17 | 997.61 |	112% |
| Dec-17 | 2,732.49 | 174% |
| Jan-18 | 3,056.53 | 12% |
| Feb-18* | 4,502.32 | 47% |

(*) to date.
