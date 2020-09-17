#Data-Science-Project

Glassdoor.com scraper and data science project
The structure from this scraper was collected at https://github.com/arapfaik/scraping-glassdoor-selenium

-The goal of this project is to collect data from Glassdoor.com then analyze company information and salary offers for data science positions across the country. To get the program to operate correctly, for this use, I had to revise every xpath as well as tune sleeps and waits to be specific for the newest version of glassdoor. 

Here is the process I used to collect it.
Web scraping is a method for collecting information from web pages and practical use of python. The challenges are Glassdoor’s library provides a limited number of data points. Glassdoor doesn’t allow you to scrape jobs or reviews. You only get to scrape companies, which didn't have value for me here. In this project, I will show you how I collected and cleaned data with selenium and sypder then performed exploratory data analysis with Jupyter Notebook.

Selenium specifically was used because Glassdoor renders its content with Javascript. Using a simple get request to the webpage would only return the visible content and I needed to go much deeper than that.

What I did was I explored data that would show me where, what industry and location and how they relate to salary. My null hypothesis was that the most jobs would come up in the bay area but rejected that hypothesis when more job searches turned up in Texas. 
 Data scientists salaries, like everyone's, reflect the seniority level of a given position. New Data Scientists can expect to enter the industry between $52,000 in Kansas and earn up to $145,000 as a senior dev in California and Texas. The two industries that reflect the most competitive salary are Oil/Gas and Game Development. In a world that is dependent on Oil to move and dependent on constant Video for stimulation it is to be expected that these industries need employees and pay well. Now the industry offering the lowest introductory pay is, I wasn't expecting this, the Architectural/Engineering industry. With constant infrastructure development and skyscrapers being erected one after the other, it was surprising to see that these companies A. didn't list more jobs and B. started employees at a base level rate. 
 
  Through the analysis of this data it was clear to see that the range of jobs a data scientist can perform is vast. Depending on your skill set you can expect to earn well into the six digit range and someone starting out, in a smaller city, can get close to those same numbers. What is very apparent in the data is getting good at being a data scientist, can set you up for a very lucrative life. 
  
  A new dev's best option for salary and cost of living for a first job would be in Texas. 

