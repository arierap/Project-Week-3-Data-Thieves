<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Data Analysis Job Market in Europe
Felipe Yuji Deguchi Hayashi, Ramón Navarro Barceló & Sara Valverde Bernuz

Data Analytics June 2020 - BCN

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
We decided to research the skills required to enter the Data Analytics job market as well as the salaries, across 7 different cities in Europe (Barcelona, Madrid, Paris, London, Dublin, Berlin and Amsterdam), with the objective of better understanding what is ahead of us once we finish the bootcamp.

## Questions & Hypotheses
We wanted to know which skills are most valuable for this psotions, at different seniority levels and potentially in different cities. 
We were also interested in the salaries and how they vary across cities and along time, as seniority increases.
We were planing on comparing the desired skills as listed by companies with the ones real people holding positions as Data Anlayst actualy have, however we could not manage to answer this one.

## Dataset
In order to get our data, we used OpenSkills API, this helped us understand what were the top skills for  a Data Analyst and allowed us to narrow down the possibilities in our next step.
We scrapped LinkedIn job listings for the 7 cities and grabbed a count of the times the skills OpenSkills had fed us were mentioned in each listing, this constituted one of our two main DataFrames.
We latter scrapped all salaries listed in GlassDoor for Data Analyst positions, which became the second DataFrame.

## Workflow
We started dividing the sources to scrapp and spent the weekend helping each other whenever we found a problem. We latter met to list possible improvements and the tasks necesary for the Data Cleaning. Ali was of great help during this part of the process, helping us solve a breaking point with the fromatting and cleaning of numerical data. We then stacked the clean data toghether and performed some transformations to allow for comparisons. 

After the data was clean and organized, we worked toghether on the visualization and insights and then organically assigned the tasks for the completion of project deliverables.

## Organization
We used Tableau as a guideline to understand at which stage of the project we were, and had regular meetings to brainstorm how to move forward.

Our Repository consits of 3 main folders; Data, Code and Images.
In Data we have 2 sub-folders, raw and clean containign the DataFrames in the before and after cleaning.
Code contains the cleanest Jupyter Notebooks we had in our personal folders.  Since ther was a lot of trial and error involved in the whole process, we have only included the code we actually endeded up using for both scrapping and cleaning.
 Finally in images we have the Database Schema.

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/ramonnavarrob/Project-Week-3-Data-Thieves.git)  
[Slides](https://drive.google.com/file/d/163dOmIQC8yrbEYAfs8iRljRgvrc3tZxh/view)  
[Trello](https://trello.com/b/SRAGf8yU/project-3)  