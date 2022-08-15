# surfs_up
Advanced Data Storage and Retrieval

## CHALLENGE OVERVIEW
---
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. 

## FEATURES AND DATA SOURCES
- Data Source: `hawaii.sqlite`
- Programming Files: `SurfsUp_Challenge.ipynb`, `climate_analysis.ipynb`
-  Data Tools: `Python SQL toolkit (SQLAlchemy)`, `Object Relational Mapper`, `pandas`, `numpy`
-  Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

## Challenge Deliverables
Deliverable 1: Determine the Summary Statistics for June
Deliverable 2: Determine the Summary Statistics for December
Deliverable 3: A written report for the statistical analysis (README.md)

## Results
---
- _Summary Statistics: June vs December Temperatures_
(june_vs_dec.png)


__Key Differences in Weather: Oahu, Hawaii__
- The average recorded temperature in June is about 75 degrees F, which is 4 degrees higher than the average temp in December.
  - This represents a -5% change in average temperature from June to December
- The frequency of temperatures recorded in June tends to have a much more even distribution
- The December temperatures seem to vary more than those in June given its larger range in recorded temperatures (min vs max temps of each month)
   
## Summary of Findings
Although temperatures in December vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by 4 degrees, and looking at the December min(56) and max(83), the conditions provided would still be warm enough to keep demand up. 

Before making a final decision, we may want to perform some additional queries to get more context on weather conditions throughout the year. We would want to consider tacking weather patterns like rain to see if rainfall may be a factor. If rainfall occurs more in December, keeping the shop open may be ill-advised as inclement weather would lower foot traffic to the area.  
