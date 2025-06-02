
# AIOPS - Why and How

With Devops - standard deployment process</br>
Waterfall to Agile for flexibility

*Automation should be*
- effeciency
- reliability
- comfort
- flexibility
- Speed of execution and Delivery

**AIOPS**-> AI capabilities in Operations<br>
Rule based: Computer metrics CPU , Memory- We have threshold(Reactive-not aware of the situation)<br>
Cpu or memory data, no live data

*AI: Proactive (Knows the context)*
Eg: From one year dat it knows that by friday it will scale up since more people use - Algo , data(userbehaviour, seasonality(festive days or other days)
Dimensions(Datascience term, eg human data (height, weight etc))- n number of data sources, live data

Datadrivern-> BUsiness usecase (dimensions) -> scrape data sources -> prepares data

dataprojects->python,K8s
three pillars of automation : PEOPLE, TECH , AUTOMATION
AIOPS components: Data, Analytics, Automation(Scrips,schedules,workbooks,playbooks)

Integrate existing systems:

Collect data and store(monitor and observe)
Analytics is on go analysis of data based on current data and context
Automation 

example with amazon
Amazon->application -> MELT configured ie scrape data in prometheous -> parse in timeseries (Time tag value) -> 
1.view in graphana and alerts set on static data
2.train the ,model with this data and create realtime alerts or scaling (models to be given by ML team)

ROADMAP: observe, engage, actions






