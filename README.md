# Global Emission Patterns Using Unsupervised Learning

---

## Introduction 

Understanding how countries differ in greenhouse gas emissions is essential for global climate change and to develop policies to reduce the effect and level of global warming on our environment. During recent times there is a lot of data collected from different sources and sensors that help us better understand the patterns and clusters across different nations using advanced unsupervised learning techniques. 

This report examines greenhouse gases and CO2 emissions across countries from the year 2000 to 2022 using a cleaned and filtered dataset from the original CO2 and greenhouse gas emission dataset [1] from our world in data [2]. Each row in the dataset represents the emission profile of the country in a particular year which results in 2,250 observations. The column represents the variables grouped into five categories: demographic indicators (eg. Country, GDP in USD, and Year),  sources of CO2 emissions (eg. total CO2, from oil, gas, coal, cement and flaring all measured in tonnes), emission intensity (eg. CO2 per capita(tonnes/person), and CO2 per gdp (tonnes/thousand usd)), global emission share (eg. Countries share of global CO2), and greenhouse gases (eg. Methane per capita, Nitrous oxide per capita in tonnes/person) , total greenhouse emissions with and without land use change (i.e urbanization , deforestation and afforestation) and temperature change from CO2 (measured in celsius) 

We apply Principal Component Analysis, Singular Value Decomposition, KMeans Clustering, and Hierarchical Clustering to identify patterns to discover how countries group based on their emission profile. Our Goal is to find Clusters to reveal how emission profiles are grouped in these past two decades to better understand our global climate goals and policies. 

---

## Theoretical Background: 

Unsupervised Learning in artificial intelligence is a type of machine learning that learns from data without human supervision [3]. Unlike supervised learning, unsupervised machine learning models are given unlabeled data and allowed to discover patterns and insights without explicit guidance or instruction [3]. Unsupervised learning is used to explore the data and understand its structure to gain meaningful insights. 

