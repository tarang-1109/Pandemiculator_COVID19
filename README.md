# Pandemiculator_COVID19
## Pandemiculator

We are developing a tool which is used for calculating the rate of infection spreding in India due to COVID -19 (Coronavirus).
Our	tool	is	based	on	using	a	mathematical	epidemic	model	to	predict	the	number	of	cases	infected	with	COVID-19	(SARS-nCOV-2	virus	caused	disease).	The	goal	is	to	predict	the	number	of	infected	cases	in	a	population	based	on	SEIR	model	to	help	the	agencies	better	understand,	mitigate,	and	suppress	its	spread.	The	model	uses	coupled	equations	analyzing	the	number	of	susceptible	people	S(t),	number	of	people	infected	I(t),	and	number	of	people	who	have	recovered	R(t).	

## Methodology

The	following	methodology	is	followed:

• Preparation	of	data	

• Grouping	data	by	growth	factor	

• Trend	analysis	

• Applying	SEIR	model	with	lockdown/wothout	lockdown	parameters	

• Factors	of	model	parameters	

• Development	of	python	code	and	implementation	of model	on	datasets	

• Scenario	in	India	

• Prediction	based	on	clinical,	population	and	epidemiology	parameters

Our	tool	will	predict	the	number	of	infected	people	in	a	given	population	in	a	future	date	if	lockdown	is	imposed	and	infected	people	without	lockdown.	The	tool	will	also	be	able	to	predict	the	dates	at	which	lockdown	may	be	lifted	or	phases.	The	tool	will	also	cluster	the	population	into	high-risk,	medium-risk	and low-risk	population	so	that	the	testing	of	the	high-risk	population	can	be	prioritized.	The	clusters	will	also	be	useful	once	we	have	the	vaccine.	The	vaccine	can	be	introduced	to	high-risk	cluster	first.	

## Expected	Outcome

1)  A	tool	for	epidemic	calculator	based	on	python	based	on	SEIR	model	

2)  The	tool	has	prediction	capability	with	lockdown	and	without	lockdown	options	

3)  Clustering	of	the	exposed	population	based	on	High-risk,	medium-risk	and	low-risk	based	on	various	based	on	various	clinical,	population	and	epidemiology	parameters	

4)  Prediction	of	the	optimal	way	to	test	the	population	as	well	as	optimal	way	of	vaccination	once	vaccine	is	available

## Data Sources

### Dataset

* Ministry	of	Health	and	Family	Welfare	,	Govt.	of	India	official	data : https://data.gov.in/major-indicator/covid-19-india-data-source-mohfw	

* Crowdsourced	COVID19-India	:	Patient	Database : https://www.covid19india.org		

* A	hub	of	Public	Datasets	for	Research	&	Innovation	on	Coronavirus : https://innovate.mygov.in/covid19/	

### SpreadSheet

* https://docs.google.com/spreadsheets/d/e/2PACX-1vSc_2y5N0I67wDU38DjDh35IZSIS30rQf7_NYZhtYYGU1jJYT6_kDx4YpF-qw0LSlGsBYP8pqM_a1Pd/pubhtml#

### Json File

* https://api.covid19india.org/raw_data.json
  
  
  
  
