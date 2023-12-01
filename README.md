# Authoritarian_International_Organization
This creates a dataset of Authoritarian International Organization for the final project of HMS 520 class. 
It is a solo work that will be used for my dissertation and follows type 3 (Analyzing a dataset that uses data wrangling and modeling tools in R)

Research Question
Does a different regime composition of an Intergovernmental Organization(IGO) lead to distinct institutional design?  

Research Goal
Methodologically, I intend to construct a better measurement of democracy at the IGO-level. Current works use an index of measuring the level of democracy for the year-IGO unit by using an average value across all the member states. This leads to various problems. Most notably, the democracy score for the United Nations and its organs ends up being a global democracy score around the world. Plus, mean value is heavily contingent on an extreme outlier, skewing the group’s overall score. I develop multiple indices and use them to check model sensitivity. Below are meant to capture different key elements to highlight, supplementing each other. 

•	Density: In order to penalize almost universal membership, density indicator penalizes large membership by dividing total volume of democracy score by the number of members. 
•	Percentage: Using DD’s dichotomous variable for democracy and autocracy, this indicator will provide a percentage of democracies taking seats in an IGO.
•	Herfindahl - Hirschman asymmetry index: This indicator measures the distribution of each member’s share of total democracy score. Although originally developed with the purpose of measuring market asymmetry, it has been applied to measure power asymmetry among members within a preferential trade agreement by McCall Smith (2000).
•	Principal component analysis (PCA): PCA is a useful way of reducing dimension when multiple vectors can be collapsed into only essential elements. Although the above three are useful stand-alone indicators, it can be useful to provide an intuitive score. 

Timeline
I have already collected relevant raw dataset, based on which I will create aggregate-level measures. 
By December 3, I will merge different country-year dataset from various sources. 
By December 5, I plan to generate four variables using dplyr and tidyr packages. 

