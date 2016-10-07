# Partner_for_real

Main file of interest at this point is CK_MA_pair1.Rmd, which contains the Rmd for pair assignment 1.

MCAgosta.R contains Marie's separate script, which is dynamically linked to CK_MA_pair1.Rmd.

Assignment 1

#Retrieving Data 

Downloaded the UKLungDeaths data from R and looked at it to get a better idea of the data available

It is composed of three time-series objects: both sexes (ldeaths), males (mdeaths) and females (fdeaths). It shows monthly deaths from bronchitis, emphysema, and asthma in the UK, 1974–1979. 

Also uses survey of drug use in the U.S. pulled from FiveThirtyEight. Does this within the Rmd itself.

#Basic Transformations on the Data 

I then proceeded to perform basic descriptive stats to get a better idea of the trends of the available data, I plotted each time-series and then plotted male and female together to see the correlation. 

The range showed the disparity in range from male to female deaths and the summary stats reinforced this. 
Male numbers are all together higher.  Both groups are strongly correlated, which is expected given what they are measuring and the time frame.

The male deaths being so much higher than female deaths could be due to environmental and occupational factors but it also could be due to cultural norms of the 1970’s as well. More research is needed to draw any causal conclusions. 

The drug survey was used to visualize commonly used drugs by age, such as alcohol and marijuana, then perform basic descriptive statistics. Some visual insights: it appears from the data that, as people age they are less likely to be a marijuana user, but if they do remain a user into their 30s they're likely to smoke as much as the kids or even more. But obviously this idea would have to be tested for statistical significance. Also, there is a strong left skew in alcohol-use data and a high standard deviation, which 
indicates wide disparities in age groups and a mean that is far lower than the median. This is to be expected given low levels of
alcohol consumption among younger age groups.


















