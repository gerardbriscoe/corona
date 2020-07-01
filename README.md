# Coronavirus Trends

This graph aims to show the trend of the Coronavirus (COVID-19) in key cities around the world.

## Graph

Modified version of the graph created by [Aatish Bhatia](https://aatishb.com/covidtrends/) in collaboration with [Minute Physics](https://www.youtube.com/user/minutephysics). This graph was chosen as it effectively represents **exponential growth** trends, which is perhaps the most [challenging aspect of pandemics](https://www.youtube.com/watch?v=Kas0tIxDvrg). The short explainer video is a clip from the Minute Physics [explainer video] (https://www.youtube.com/watch?v=54XLXg4fYsc).

## Views

### Cities

There is a lack of graphs focusing on cities, especially in showing their current and trending situation. So, [past research](https://www.rca.ac.uk/research-innovation/research-centres/helen-hamlyn-centre/research-projects/2018-projects/global-healthcare-index/) on identifying key cities for creating global indices was used to include a selection as shown:

|South America| North America  | Europe | Asia | Middle East | Africa | Oceania|
|:--------------|:--------------|:-------|:-----|:------------|:-------|:-------|
| Sao Paulo | New York | London | Tokyo | Dubai | Johannesburg | Sydney |
| Buenos Aires | Toronto | Paris | Shanghai | Istanbul | Lagos | Auckland |
| Bogota | Mexico City | Berlin | Singapore |Riyadh  | Casablanca | Honolulu |
| Santiago | Los Angeles | Milan | Hong Kong |Tel Aviv| Tunis | Melbourne |
| Caracas | Montreal | Madrid | Mumbai | Cairo| Kampala | Wellington |
| Lima | Chicago | Moscow | Seoul | Doha | Luanda | Brisbane |
| Rio de Janeiro | Vancouver | Amsterdam | Jakarta | Abu Dhabi | Dar es Salaam | Christchurch |

Selecting 7 cities per region based upon Loughborough University’s [City Link Classification](https://www.lboro.ac.uk/gawc/world2018link.html) (connectivity), nation diversity, as well as city, national and regional contributions to Global Domestic Product (GDP). 

The graph by design does not show locations that are yet to reach 50 cases, so any of these cities not currently showing on the graph are fortunate enough to lack 50 reported cases.

### Countries

A plot for the European Union (EU) and the World was added to the original graph. The countries used for calculating the EU includes those with free movement via the European Economic Area (EEA). This includes the European Free Trade Association (EFTA) states of Iceland, Liechtenstein, Norway, Switzerland; and the United Kingdom (UK) that remains a member during the transition period of Brexit.

### Regions

A plot for the 7 regions of the World, 6 continents model plus the Middle East as a distinct cultural region. Russia is split across Europe and Asia proportionally according to population, resulting in roughly 70% of cases assigned to Europe and 30% assigned to Asia. 

### National

The plots for China, United States, Canada, Australia were modified to include available cities, regions and the World to provide greater context. A plot for the UK was also added, but Northern Ireland could not be included as no time series could be found or constructed.

### London

A plot of the boroughs of London, which includes London as a whole to provide context.

### Locations

A view that allows the selection of all available locations, with the default plot showing a full location hierarchy from a London borough to the entire World.

### Governance

A plot of countries grouped by their governance model, based upon the [Economist](https://www.economist.com/)'s [Intelligence Unit](https://www.eiu.com/n/)'s [Democracy Index (2019)](https://www.eiu.com/topic/democracy-index). Their scale ranges from 0-10, but as it is not evenly divided at the lower end the groupings were adjusted:

| Type | Range | Countries |
|:-----|:------|:----------|
| Full Democracies | 8-10 | Norway, Iceland, Sweden, New Zealand, Finland, Ireland, Denmark, Canada, Australia, Switzerland, Netherlands, Luxembourg, Germany, United Kingdom, Uruguay, Austria, Spain, Mauritius, Costa Rica, France, Chile, Portugal,  |
| Flawed Democracies | 6-8 | South Korea, Japan, United States of America, Malta, Estonia, Israel, Botswana, Cabo Verde, Taiwan, Czech Republic, Belgium, Cyprus, Italy, Slovenia, Lithuania, Latvia, Greece, South Africa, Timor-Leste, Slovakia, Malaysia, Trinidad and Tobago, Colombia, Panama, Bulgaria, Argentina, Suriname, Jamaica, India, Brazil, Tunisia, Philippines, Ghana, Hungary, Poland, Peru, Croatia, Dominican Republic, Lesotho, Mongolia, Romania, Indonesia, Namibia, Serbia, Ecuador, Thailand, Sri Lanka, Paraguay, El Salvador, Guyana, Mexico, Papua New Guinea, Hong Kong, Singapore  |
| Hybrid Regimes | 4-6 | North Macedonia, Ukraine, Albania, Bangladesh, Fiji, Senegal, Moldova, Montenegro, Madagascar, Armenia, Malawi, Liberia, Georgia, Honduras, Bhutan, Nepal, Guatemala, Kenya, Tanzania, Morocco, Benin, Zambia, Uganda, Mali, Kyrgyz Republic, Bosnia and Hercegovina, Sierra Leone, Bolivia, Haiti, Lebanon, Gambia, Pakistan, Nigeria, Turkey, Côte d’Ivoire, Burkina Faso, Algeria  |
| Less Authoritarian | 2-4 | Jordan, Kuwait, Mauritania, Palestine, Iraq, Angola, Mozambique, Gabon, Myanmar, Nicaragua, Cambodia, Ethiopia, Togo, Niger, Qatar, Rwanda, Zimbabwe, Comoros, eSwatini, Guinea, Congo (Brazzaville), Russia, Vietnam, Egypt, Oman, Kazakhstan, Venezuela, Afghanistan, Cameroon, Cuba, Djibouti, United Arab Emirates, Azerbaijan, Sudan, Guinea-Bissau, Bahrain, Belarus, Iran, Eritrea, China, Burundi, Laos, Libya, Uzbekistan |
| More Authoritarian | 0-2 | Yemen, Saudi Arabia, Tajikistan, Equatorial Guinea, Turkmenistan, Chad, Syria, Central African Republic, Democratic Republic of Congo, North Korea |


## Data Sources

* Cities Data comes from a range of sources:
	- mostly city governments that provide direct sources
	- many state or national data sources (several identified from the [Corona Data Scraper](https://coronadatascraper.com/))
	- several use an amalgamation of different sources to provide a time series
	- couple directly from the Countries Data
	- one from national counties data
	- a small number were scaled from:
		- country data by past reported cases
		- country data by population
* Countries Data comes from [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19), as with the original graph.
* Regional Data is calculated from the Countries Data.
* National Data was constructed:
	* from the above data sources
	* and UK's [Public Health England](https://coronavirus.data.gov.uk/), [Public Health Scotland](https://www.gov.scot/publications/coronavirus-covid-19-trends-in-daily-data/) and [Public Health Wales](https://phw.nhs.wales/topics/latest-information-on-novel-coronavirus-covid-19/coronavirus-grid-links/coronavirus-covid-19-data-dashboard-desktop-view/).
* London Data comes from [Public Health England](https://coronavirus.data.gov.uk/).
* Locations Data is an amalgamation of the above data sources.
* Governance Data was calculated from the Countries Data.