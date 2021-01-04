# EJ Index in Transportation for Mexicali

In this repository you'll find a shapefile with indicators reflecting the environmental burden percentile for each geographic unit (AGEB) in Mexicali, Baja California.

The shapefile contains the following attributes, which are all detailed in Q1 report to EPA/NADBANK:

## Geography
- CVEGEO: AGEB id

## Pollution indicators
- pm25: PM 2.5 aggregated and interpolated levels (Source: SINAICA, 2015–2017)
- pm25percentile: Percentile ranking for "pm25" variable
- pm 10: PM 10 aggregated and interpolated levels (Source: SINAICA, 2015–2017)
- pm10percentile: Percentile ranking for "pm10" variable
- o3: O3 aggregated and interpolated levels (Source: SINAICA, 2015–2017)
- o3percentile: Percentile ranking for "o3" variable
- traffic: traffic congestion aggregated levels (Source: Waze)
- trafficpercentile: Percentile ranking for "traffic" variable
- POLLUTIONa: Aggregated Pollution indicator, with equal weighting between the variables described above.
- POLLUTIONp: Percentile ranking for "POLLUTIONa" variable

## Population indicators
- asthma: asthma aggregated levels (Source: Secretaría de Salud)
- asthmapercentile: Percentile ranking for "asma" variable
- indigenous: indigenous population levels (Source: CENSO 2010)
- indigenpercentile: Percentile ranking for "indigenous" variable
- vulnerable: vulnerable population ages (<6 and >65 years old; Source: CENSO 2010)
- vulnerabpercentile: Percentile ranking for "vulnerable" variable
- population: total population levels (Source: CENSO 2010)
- populatipercentile: Percentile ranking for "population" variable
- mobility: mobility disabilities (Source: CENSO 2010)
- mobilitypercentile: Percentile ranking for "mobility" variable
- imu: marginalization index values (Source: CONAPO 2010, https://www.gob.mx/conapo/documentos/indice-de-marginacion-urbana)
- imupercentile: Percentile ranking for "imupercent" variable
- POPULATION: Aggregated Population indicator, with equal weighting between the variables described above.
- POPpercentile: Percentile ranking for "POPULATION" variable

## Final EJ Index 
- BOTHCombin: Aggregated indicator built from the "POLLUTIONa" and "POPULATION" indicators
- BOTHPercen: Percentile ranking for "BOTHCombin" variable
