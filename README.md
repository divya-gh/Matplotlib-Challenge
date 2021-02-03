# Matplotlib-ChallengeMatplotlib - The Power of Plots## Data Munging and Analysis of anti-cancer pharmaceutical Drug Regimens'.## Table of contents* [Introduction ](#introduction )* [Objectives ](#objectives)* [Observations](#observations)* [Technologies](#technologies)* [Code](#code)* [Status](#status)* [Acknowledgement ](#acknowledgement )* [Contact](#contact)## Introduction__Pymaceuticals__  : *Pharmaceutical company based out of San Diego , specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In their most recent study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured.*### Objectives - Compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. - Generate all of the tables and figures needed for the technical report of the study.- Generate top-level summary of the study results.## ## Observations and Insights - __1. Summery Statistics of Tumer Volume (mm3):__  	       - __Drugs  "Capomulin ,Ramicane and Ceftamin":__          - Above drugs show promising results on reducing the overall 'Tumer Volume' over 'Time'. They           have lower variance between the observations and also low deviation form the mean.                             - Observations are normally distributed without the outliers.                                   - __Drugs  "Ketapril, Neftisol, Placebo, Propriva and Stelasyn":__          - Above drugs have higher variance between the observations and also greater deviation from the            mean .                                   - This proves that Tumer sizes are not normally distributed over time and there could be             some outliers.           - Plotting Avg. Tumer volume vs Time for the above drugs will provide a clear picture of their             effectiveness on reducing the overall size of the Tumer over time.- __2. Male/Female Ratio:__ 	- From the Pie chart it is clear that in the the overall study of 'Drug Regimen' , we have more            Male mice vs Females.          - To uncover drug effectiveness by gender, we need further analysis of Avg. Tumer Volume over           time by gender for each 'Drug Regimen'. This would provide us with better understanding of its            effectiveness based on the category.	 - __3. Capomulin Analysis:__ 	 - Deep analyis on 'Capomuline' on a single mouse(s185) shows a significant reduction in Tumer               Volume(mm3)  just in 45 days, which is very promising.         - Scatter plot of 'Avg. Tumer Volume vs Weight' and 'Calculation of Correlation Coefficient' which is '0.84' for Capomuline, determine that 'Tumer size' and 'Mouse Weight' are positively related.		- This analysis can be used to control weight during the course of treatment well as gather 		   insights on duration and dosage of prescription "Capomulin"  based on the weight scale.### Overall Summery:                 1. Drug Regimen "Capomuline" is leading in reducing the Tumer Size within the short period of                    time (45 days) and can be the top recommendation for the treatment.                 2. Drug Regimen "Ramicane" also shows promising results and can be considered for treatment                     as well. Further investigation and analysis might be needed for better comparison between                     the two.                 3. Linear regression Model for Capomuline shows that there is a positive correlation between                    'Tumer Volume and Weight', which should be taken into consideration during the course of                    treatment.                4. Analysis on 'Metastic increase' and 'No. of mouse survived' over the course of treatment,                     might uncover further insights on "Capomuline" and other Drug Regimen.## Technologies* git Bash* Jupyter notebook### Python Modules and libraries* pandas * scipy* matplotlib.pyplot* numpy## Code - [HeroesOfPymoli Script](/HeroesOfPymoli/HeroesOfPymoli_starter.ipynb)-  __Nbviewer.jupyter Display :__	 *  [HeroesOfPymoli Script](https://nbviewer.jupyter.org/github/divya-gh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli_starter.ipynb).## StatusProject Complete## Acknowledgement - Homework discussion with Courtney Gomez## ContactCreated by [Divyashettyk@gmail.com](#divyashettyk@gmail.com)