# Air Quality Prediction Model
<img src="https://cdn.who.int/media/images/default-source/air-pollution/air-pollution-mix-of-outdoor-and-indoor-air-pollution.tmb-1366v.jpg?sfvrsn=b5fbc279_3" width="550">

*[According to **IQAir** (https://www.iqair.com)]*<br>

"During 2019, according to figures published by IQAir.com, the average level of air pollution in Italy was 61 USAQI which placed it in the “Moderate “class and ranked it in position 59 out of a total of 98 countries.<br>
During the 1990s Italy held the tenth position as the country which produced the most carbon dioxide (CO2). Heavy traffic and congestion in the large metropolitan areas continue to be a main source of pollution even though smog levels have fallen since the 70s and 80s. Two of the larger northern cities such as Milan and Turin have some of the worst air pollution in all of Europe and in December 2017 introduced traffic restrictions in order to try to improvethe quality of the air. As early as 2011, officials realised that pollution, in general, was reaching critical levels and that the problem needed addressing.

In 2018 air quality levels were reaching a “red” alert status [...] causing breathing and heart problems and is attributed with over 9 per cent of deaths of Italians over the age of 30 years."<br>

## Key Information about Air Pollution
### What is Air Pollution
Air pollution is contamination of the indoor or outdoor environment by any chemical, physical or biological agent that modifies the natural characteristics of the atmosphere.

Household combustion devices, motor vehicles, industrial facilities and forest fires are common sources of air pollution. Pollutants of major public health concern include particulate matter, carbon monoxide, ozone, nitrogen dioxide and sulfur dioxide. Outdoor and indoor air pollution cause respiratory and other diseases and are important sources of morbidity and mortality. 

WHO data show that almost all of the global population (99%) breathe air that exceeds WHO guideline limits and contains high levels of pollutants, with low- and middle-income countries suffering from the highest exposures.

Air quality is closely linked to the earth’s climate and ecosystems globally. Many of the drivers of air pollution (i.e. combustion of fossil fuels) are also sources of greenhouse gas emissions. Policies to reduce air pollution, therefore, offer a win-win strategy for both climate and health, lowering the burden of disease attributable to air pollution, as well as contributing to the near- and long-term mitigation of climate change.

### What are the health hazards from breathing in the dirty air?
Carbon monoxide (CO) and lead (Pb) suspended in the air can contribute to ill effects. The main air pollutants include particulate matter, followed by carbon (C), sulphuroxides (SO), nitrogen oxides (NO), ammonia (NH3), carbon monoxide(CO) and methane (CH4).<br>

According to the World Health Organisation, exposure to air pollution causes 4.2 milliondeaths worldwide, and cause at least 600,000 children to suffer from acuterespiratory infections, caused by toxic air. There are nearly 500,000 prematuredeaths in Europe every year. Exposure to carcinogenic particulate matter, nitrogen dioxide (NO2) and ground-level ozone (O3) costthe lives of 76,200 people in Italy in just one year, reveals the European Environment Agency.

## Using Machine Learning to Predict Air Pollution
<img src="https://static.vecteezy.com/system/resources/thumbnails/014/265/576/small/person-holding-a-tablet-technology-looking-at-the-graph-of-pollution-reduction-or-contaminants-toxic-substances-in-industrial-plants-to-obtain-an-environmental-certificate-photo.jpg" width="250">

### The Dataset
The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level, within an Italian city. Data were recorded from March 2004 to February 2005 (one year), representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer. Evidences of cross-sensitivities as well as both concept and sensor drifts are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors concentration estimation capabilities. Missing values are tagged with -200 value.
This dataset can be used exclusively for research purposes. Commercial purposes are fully excluded.<br>

#### Chemical Formulas
- CO: **Carbon Monoxide**


***Reference Links:***<br>
[*Dataset Reference*]: https://archive.ics.uci.edu/ml/datasets/Air+Quality <br>
[*Dataset*]: https://archive.ics.uci.edu/ml/machine-learning-databases/00360/ <br>
