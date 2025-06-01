#AIOPS - Why and How
With Devops - standard deployment process
Waterfall to Agile for flexibility

Automation should be
1.effeciency
2.reliability
3.comfort
4.flexibility
5.Speed of execution and Delivery

AIOPS-> AI capabilities in Operations
Rule based: Computer metrics CPU , Memory- We have threshold(Reactive-not aware of the situation)
Cpu or memory data, no live data

AI: Proactive (Knows the context)
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






