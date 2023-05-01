# Coronavirus Twitter Analysis: 2020
This project was for my Data Structures and Algorithms class at CMC (Claremont McKenna College). The objective of this project was to get comfortable using the MapReduce technique and shell script commands to process large amounts of data, with this particular dataset being billions of tweets sent in 2020.

I used four different python programs to analyze this data: `map.py`, `reduce.py`, `alternative_reduce.py`, and `visualize.py`. The `map.py` file looks through all files passed into it and then determines the country origin and language of the tweet. The `reduce.py` takes multiple files, those of which are the output files of map.py, and combines them all into one file. `visualize.py` then generates bar graphs from the results of the top ten keys in each input file, and saves them as png files. 


**Coronavirus Hashtags by Country of Origin**


<img src=coronavirus_country.png width=100% />

**Coronavirus Hashtags by Language**

<img src=coronavirus_lang.png width=95% />

**코로나바이러스Hashtags by Language**

<img src=코로나바이러_lang.png width=95% />

**코로나바이러스Hashtags by Origin**
<img src=코로나바이러_origin.png width=95% />


**Alternative.reduce (Combination of Reduce and Visualize)**
For the `alternative_reduce.py` portion of the project, I combined the structures of reduce and visualize into one file which would take different words as keys to compare their usages in tweets from 2020. For this particular graph I compared the use of #covid19, #coronavirus, #PPE, and #nurse.

 <img src=covid19_coronavirus_PPE_nurse.png width=95% />

