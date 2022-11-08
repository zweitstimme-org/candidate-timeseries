# candidate-timeseries

This repo contains all of the zweitstimme.org district predictions from September 1 to September 26 2021. 

The file `district_timeseries.RDS` contains a list with one entry for each day. For each day it contains a list with one entry for each of the 299 districts. For each of the districts it contains a data frame with the following fields:
- `Wkr`: The district number
- `Wkr_Name`: The district name
- `Partei`: The name of the party of the candidate
- `auf_Liste`: Dummy variable. Did the candidate also run on a list?
- `Listenplatz`: What slot on the list did a candidate have?
- `win_prob`: The probability of winning the district according to the zweitstimme.org model.