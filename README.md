# worldprisonbrief
Data from the World Prison Brief Database for Stata (17.08.2022)

These data were obtained from the World Prison Brief Database (WPB): https://www.prisonstudies.org/world-prison-brief-data

Data were collected between 15.08.2022-17.08.2022

Countrycodes (ISO) and countrynames, region, region names, incomelevel (and names) were drawn from the World Bank via wbopendata. Countries that are not part of the World Bank are therefore not included: Mayotte (France), Reunion (France), Taiwan, Anguilla (UK), Guadeloupe (France), Martinique (France), Guernsey (United Kingdom), Jersey (United Kingdom), Cook Islands (New Zealand), French Guiana/Guyane (France). Two countries - UK and Bosnia and Herzegovina - are reported as regions (UK: England & Wales, UK: Northern Ireland, UK: Scotland; Bosnia and Herzegovina: Federation, Bosnia and Herzegovina: Republika Srpska) in the WPB. These regions where combined using linear interpolation for missing years and weighted in accordance to their share of the population. 

The variable prisoncomment includes the notes as provided in the WPB (with exception of "i"): x=newest number, often mid-year, often estimate; c=circa/estimate; p=including estimate in police stations, i=based on linear interpolation of at least one value (Herzegovina, UK), j=Convicted prisoners only (Brazil, Jamaica). 

Values for Rwanda do not include genozide related incarcerations (see file Rwanda for values including genozide related incarcerations). 
