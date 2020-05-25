# Pandemiculator : A Pandemic calculator for estimating population epidemiology scenario in India
## Pandemiculator

Pandemiculator (Pandemic Calculator) is based on using statistical and mathematical epidemic models to predict the number of cases infected with COVID-19 (SARS-nCOV-2 virus caused disease). The goal is to showcase the current scenario in India and predict the number of infected cases using regression in a population along with the growth factor using mathematical models like SEIRD to help the agencies better understand, mitigate, and suppress its spread. The clustering of population can help in inderstanding risks based on clinical parameters of various age group and also to develop vaccinnation strategy once vaccinne is developed with the help of SEIRV model.

## Methodology

The	following	methodology	is	followed:

• Preparation	of	data	

• Grouping	data	by	growth	factor	

• Trend	analysis	

• Applying	SEIRD	model	with	lockdown/wothout	lockdown	parameters	

• Factors	of	model	parameters	

• Development	of	python	code	and	implementation	of model	on	datasets	

• Scenario	in	India	

• Prediction	based	on	clinical,	population	and	epidemiology	parameters

Our	tool	will	predict	the	number	of	infected	people	in	a	given	population	in	a	future	date	if	lockdown	is	imposed	and	infected	people	without	lockdown.	The	tool	will	also	be	able	to	predict	the	dates	at	which	lockdown	may	be	lifted	or	phases.	The	tool	will	also	cluster	the	population	into	high-risk,	medium-risk	and low-risk	population	so	that	the	testing	of	the	high-risk	population	can	be	prioritized.	The	clusters	will	also	be	useful	once	we	have	the	vaccine.	The	vaccine	can	be	introduced	to	high-risk	cluster	first.	


### Curret Senario of COVID-19 in India

 Live Update of COVID-19 in India Graphical Representation 
![](/images/Daily_update.png)

 Live Update of COVID-19 on India Map
![](/images/India_Map.png)


### SEIRD Model
The	SEIRD Model	uses	coupled	equations	analyzing	the	number	of	susceptible	people	S(t),	number	of	people	infected	I(t), number of dead people D(t) and number	of	people	who	have	recovered	R(t).	

![SEIRD Model](/images/SEIRD.png)


In a closed population with no births or deaths, the SEIRD model becomes:

![](/images/model.png)

where N = S + E + I + R + D is the total population.

SEIRD Model on Indian Data
![](/images/SEIRV.png)


## Expected	Outcome

1)  A	tool	for	epidemic	calculator	based	on	python	based	on	SEIRD	model	

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

### JSON File

* https://api.covid19india.org/raw_data.json

## Reference 

1) https://www.kaggle.com/allen-institute-for-ai/CORD-19-researchchallenge/tasks	

2) Peng,	Liangrong,	Wuyue	Yang,	Dongyan	Zhang,	Changjing	Zhuge,	and	Liu	Hong.	"Epidemic	analysis	of	COVID-19	in	China	by	dynamical	modeling."	arXiv	preprint	arXiv:2002.06563	(2020).	

3) https://www.eetindia.co.in/Covid-19-The-Power-of-AI-and-Big-Data/	

4) https://en.wikipedia.org/wiki/Kermack–McKendrick_theory	

5) Age-structured	impact	of	social	distancing	on	the	COVID-19	epidemic	in	India	:	Rajesh	Singh,	R.	Adhikari	(https://arxiv.org/abs/2003.12055)

6) SEIR	and	Regression	Model	based	COVID-19	outbreak	predictions	in	India	Gaurav	Pandey,	Poonam	Chaudhary,	Rajan	Gupta,	Saibal	Pal	(https:// arxiv.org/abs/2004.00958)	

7) SEIRD model for COVID-19 (https://medium.com/@djconnel_14663/seird-model-of-covid-19-596e6754c2c4)

8) Nguyen, Chantal, and Jean M. Carlson. "Optimizing real-time vaccine allocation in a stochastic SIR model." PloS one 11, no. 4 (2016).
  
  
  
  
