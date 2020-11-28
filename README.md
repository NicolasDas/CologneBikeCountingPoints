# CologneBikeCountingPoints
Parse and analyse cologne bike counting points

The city of Cologne published data of its bike counting points on the website: http://www.eco-public.com/ParcPublic/?id=677

This notebook provides functions to parse the above website, download the data, and do some analysis.
Bike and weather data until Oct 20 is provided in two csv files in this repository.

Weather data was taken from this source: https://meteostat.net/de/station/10513

## Dependencies
In order to run this notebook, you need to install the following dependencies:
```
pip3 install holidays==0.10.3 cufflinks==0.17.3 pandas==1.1.3 plotly==4.11.0 statsmodels=0.12.1 requests=2.18.4
```
