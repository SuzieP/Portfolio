# Data Analysis Personal Projects - Sotiria (Suzie) Papantoni
----------------

#### [1. Multivariate quantitative analysis and visualization of L&D survey data (records for 2018-2020 collected by Emerald Works UK) using Python.](https://nbviewer.jupyter.org/github/SuzieP/Portfolio/blob/master/EmeraldWorks%20L%26D%20survey%20analysis%20and%20dashboard.ipynb)
###### The dataset

The dataset comes in an excel file provided by the L&D research organization Emerald Works and contains 3 years’ worth of data collected from learning and development leaders and their organisational learning strategy.  In total there are 1697 rows of respondents and 293 variables in the dataset.

###### The analysis

I conducted an exploratory analysis of the survey results that unveiled the significance of Learning & Development strategies in organizational performance, the top L&D skills achieved and top L&D skills needed across 2018-2020 as well as the top L&D barriers across 2018-2020.

###### The results 

An interactive dashboard with the results of my analysis on plotly can be found [below](https://chart-studio.plotly.com/~spap/7/ew-ld-data-2018-2020/)
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/dashboard/spap:7/embed"></iframe>

#### [2. Exploratory correlation analysis of the Chicago govt. public datasets (published in 2012) using SQL and Python.](https://nbviewer.jupyter.org/github/SuzieP/Portfolio/blob/master/Chicago-%20school%2C%20socioeconomics%2C%20and%20crime.ipynb)
In this project I explored the relationships between the variables in three different datasets pulled from the Chicago government website and stored in a DB2 database: 
 1. Socioeconomic indicators in Chicago for each community area for years 2018-2012
 2. Chicago public school records for the 2011-2012 school year
 3. Chicago crime data from 2001 to 2012  

I conducted an exploratory correlation analysis between the following variables:
* per capita income
* hardship index
* crime count
* safety score
* college enrollment rates
* school misconduct rates

#### [3. Web Scraping with Twitter API, content analysis and WordCloud visualization using Python.](https://github.com/SuzieP/Portfolio/blob/master/twitter-trump/twitter-trump.md)

In light of the Capitol Hill riots and the subsequent ban of Donald Trump's account on Twitter, I performed an exploratory content analysis of all tweets that mention Donald Trump posted between January 5 to January 8 2021.  

I created a simple algorithm to calculate the ‘newsworthiness' of each word on a given day, aka how frequent the word is on that day vs on other days. The distribution of this value across words was then visualized through WordCloud for each day. The result is a visual story of the daily news surrounding Donald Trump as seen through Twitter. 

#### [4. Citation network analysis using Python's PageRank algorithm and visualization (dataset published by AMiner in 2010).](https://nbviewer.jupyter.org/github/SuzieP/Portfolio/blob/master/Citation%20Network%20with%20PageRank.ipynb) 

This is a collaborative project and an exploratory network analysis of this [Citation-Network V1](https://www.aminer.org/citation) containing research citation data for 629,814 papers and 632.752 citations. We wanted to generate the most important papers in this dataset according to how often it was referenced by other papers. So we built a network in which every node was a single paper and every edge was a reference to another paper. We ran the PageRank algorithm on a subgraph of the data to determine which nodes were the most important. We also explored some additional properties of the dataset such as weakly connected components and betweenness centrality to facilitate our understanding of the citation data. 

<img src="https://raw.githubusercontent.com/SuzieP/Portfolio/master/Citation%20network%20pseudocode.png">

#### [5. Data visualization of Hollywood's most profitable stories (pulled from InformationisBeautiful for 2008-2011) using Tableau.](https://public.tableau.com/views/MostProfitableHollywoodStories2008-2011/HollywoodStories?:language=en&:display_count=y&:origin=viz_share_link)

<div class='tableauPlaceholder' id='viz1612920013930' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MostProfitableHollywoodStories2008-2011&#47;HollywoodStories&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MostProfitableHollywoodStories2008-2011&#47;HollywoodStories' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MostProfitableHollywoodStories2008-2011&#47;HollywoodStories&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>  

<iframe width="900" height="955" src="https://public.tableau.com/views/MostProfitableHollywoodStories2008-2011/HollywoodStories?:language=en&:display_count=y&:origin=viz_share_link&:showVizHome=no"></iframe>


#### [6. Data visualization of Trump's approval ratings (pulled from FiveThirtyEight on Nov 2020) using Python and Tableau.](https://nbviewer.jupyter.org/github/SuzieP/Portfolio/blob/master/Tracking%20Trump%27s%20approval%20and%20disapproval%20ratings.ipynb)

<div class='tableauPlaceholder' id='viz1612645991983' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16126446592990&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_16126446592990&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='no' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16126446592990&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>

<iframe width="950" height="755" src="https://public.tableau.com/views/Book1_16126446592990/Dashboard1?:language=en&:display_count=y&:toolbar=n&:origin=viz_share_link&:showVizHome=no"></iframe>
