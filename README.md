  This project is another project from the [data_science_project](https://github.com/shpark61/data_science_project) which I participated in.
## Project description 
  The aim in this project was to find the correlation between various life factors to life expectnacy. I expected that GDP would have one   of the strongest correlation with life expectancy.
  
  Prior to settling with this topic, I had been looking around a topic concerning suicide rates and the happiness level. Even though I  could find data regarding the two topics, I was unable to find a way to express the correlation or causation that could be found by comparing the two datasets. Luckily, I was able to stumble in this topic and reach a fair conclusion using the data I found.

## Data description
  The data was found in a well-known data community site called [Kaggle](https://www.kaggle.com/).
  - [Data 1](https://www.kaggle.com/kumarajarshi/life-expectancy-who): shows the life expectany for 260 nations since 1800 to 2016
  - [Data 2](https://www.kaggle.com/amarpandey/world-life-expectancy-18002016): shows the life expectancy for 194 countries from 2000 to 2015 and immunizaiton, expenditure, lifestyle-related data
  
## Technology
  Python 3 was the language used similar to the previous project for the use of "pandas' and "matplotlib" libraries to process, merge, and visualize data easily. All the files and contents were edited on an online web application, [Juypter Notebook](https://jupyter.org/).
  
  Documentation of previously mentioned libraries, pandas and matplotlib, can be found below:
  - [pandas 0.25.0 documentation](https://pandas.pydata.org/pandas-docs/stable/)   
  - [matplotlib 3.1.1 documentation](https://matplotlib.org/3.1.1/contents.html)
  
## Data Analysis
![line_graph_1](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/line_graph_1.png)
  The line graph above was created from data 2 which included the annual life expectancy of 200+ countries from 1800 to 2016. The graph shows a steady increase in life expectancy since 1800 due to better implementation of hospitals and more discoveries on cures. However, there are noteworthy drops in the graph in 1917, the 1930s and 1940. All these three years have significant relevance to the war or lack of necessities than other times. In 1917, World War I started to be in process and created the death of many men and in result caused the great decline in life ecpectancy. In the 1930s, the Great Depression caused the lack of food and various necessities. In 1940, World War II happened, and significant drop in life expectancy can be seen. Interestingly, World War II had drop less than World War I when in fact there was the massacre of the Jews and the nuclear bomb dropped in Japan.

![hist](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/hist.png)
  The histogram above was created from data 1 which was collected from only 2000 and therefore lacks a lot of data than data2. The most frequent life expectnacy was around 73 which is similar to the global annual life expectancy of 2015. To look deeper into frequent life expectancies, data1 was divided into two groups: developing and developed countries. The difference in the life expectancies of the developing and developed countries was 11 years, and this phenomenon was probably observed due to more open and public health-related facilities and systems found in developed countries for the general wellfare while the developing countries are still lacking systems for wellfare since they are persisiting to improve their economy primarily. 
  
![scatter_plot_1](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/scatter_plot_1.png)
  The scatter plot above was created from data 1 for comparing individual and government expenditures to life expectancy. Individual expenditure had shown more correlation with life expectancy than the government expenditure. Althought the government's investments on its citizens' health may look more influential, indivduals investing on their own health may be more detailed and suitable for him or herself.

![scatter_plot_2](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/scatter_plot_2.png)
  The scatter plot above was created from data 1 for comparing immunization-related factors to life expectancy. The immunization-related factors were vaccination of Hepatitis B, vaccination of Diphtheria, vaccination of Polio, occurence of measles, HIV/AIDS, and prevalence of thinness. The scatter plots located on the first show a positive correlation such that immunization of certain diseases can help extend one's life expectancy. The scatter plots located on the bottom show a negative correlation such that fewer occurences of diseases or malnourished children probably led to longer living children and likewise impacted the life expectancy.

![scatter_plot_3](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/scatter_plot_3.png)
  The scatter plot above employed data 1 and compares several life-style related factors to life expectancy. All the lifestyle-related factors have a high correlation with life expectancy except population. Perhaps population has a low correlation with life expectancy because the world's population is not at a point where it is too crowded with people and unpleasent to live. Alcohol, Body Mass Index(BMI), and GDP have similar correlations. A high consumption of alcohol can also mean the country does not have a low gdp and therefore a relatively medium or high BMI than other countries which have a low consumption of alcohol. The last two variables, Human Development Index(HDI) and years of education, show the highest correlation out of all the factors compared to life expectancy of 0.72 and 0.73. Since HDI takes account of life span, it does make sense that a high correlation was observed. Education was the most important variable to have a long life span. Education especially in kindergarden or elementary school tells young students to be sanitary and be clean which might lower the occurence of harmful diseases and extend the life expectancy.

![scatter_plot_4](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/scatter_plot_4.png)
  The scatter plot above was created from data 1, comparing mortality factors to life span. All the mortality-related variables had a negative correlation. all the mortality rates of adults, infants, and under-five show a correlation which was not really out of mind, but the correlation of Aault mortality is really high compared to the infant and under-five death rates.

![scatter_plot_5](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/scatter_plot_5.png)
  Since the first scatter plot which compared expenditure with life span did not have greate correlation, a new dataset was creaetd for data which had less than 65 years of life expectancy. Apart from the first scatter plot, the scatter plot above had a negative correlation and had less correlation than the previous one. Perhpas countries with lower life expectancy do not possess enough health-related infrastructure for the citizens and therefore has low effect on the life span whatever the government expenditure is.

![scatter_plot_6](https://github.com/jeed123456789/data_science_project2/blob/master/graphs/scatter_plot_6.png)
  The last scatter plot compared the factors that had higher than 0.5 or lower than -0.5 correlation for developing and developed countries. Suprisingly, HIV/AIDS had nearly no correlation to the life span for the developed countries while developing countries still showed a high correlation of -0.615. Likewise, there was a low correlation of BMI to life span in developed countries compared to the developing countries which had a correlation of 0.524. Sthe scatter plot was plotted generally, the correlation was high, and this could have been observed since there are 83% countries that are developing and only 17% countries developed. 

## Conclusion
## Possible Extensions
