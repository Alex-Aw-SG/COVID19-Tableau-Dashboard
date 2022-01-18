# COVID19-Tableau-Dashboard

Disclaimer:
This is purely an academic project to show my proficiency in Tableau and Analytic skills. This analysis is not to proof, debate, or confirm the benefits or drawbacks of  vaccinations. 

Project Background:  
In early 2021, Singapore Government was introducing Pfizer & Moderna vaccines to the general population. At that time, only frontline workers and selected individuals were given the vaccines locally, hence limited data were available to the public. Even globally, information on the new mRNA vaccines severe side effects were limited as the world pushed forward to vaccinate and protect the population. The most widely available data were at https://vaers.hhs.gov/, consolidated based on voluntary submission of information. 

Objective:    
Using data from VAERS, date ranging from 12th Jan 2020 - 15th Apr 2021, to carry out descriptive data analysis using Tableau to gain insights. In conjuction, a dashboard was created that would enable live updates whenever new data was available. With the insights, anticipated side effects can be used for preventive measures and public awareness on getting vaccinations. 

Problems encountered:   
Data was very dirty and incomplete. Majority of the submission were done by individuals on voluntary basis, therefore reporting standards were inconsistent. Vital information may be lacking, for example actual cause of death were not reflected or verified, hence it is uncertain whether death cases were due to the vaccine, COVID-19 or other issues. Free text input may include existing health conditions of individuals, but it may also include a list of conditions they do NOT possess, therefore complicating actual conditions analysis purely by pre-processing the data.

Insights gained and verified:   
During early scoping of the project (March 2021), initial analysis indicated several noteworthy trends. For example, women tend to experience more severe side effects than men. It was published in many news outlet around April-May 2021 to confirm our analysis. 

Files included in the repo:   
- COVID19-Dashboard.twbx : Tableau file that consist of dashboard and the data   
- VAERSdata.rar : Raw data extracted from VAERS website   
- VAERSDataUseGuide_November2020.pdf : Data dictionary provided by VAERS   
