# COVID-19 in Australia
Analyse data about development of COVID-19 in Australia. The data are from COVID Live (https://covidlive.com.au/). 
**Data**
The data cover 5 mainland states in Australia – NSW, Vic, QLD, SA, WA – and represent information about the numbers of new cases (files daily_cases) and new deaths (files daily_death). 
Important note: despite files names there is a mix of data – daily numbers before September 9, 2022, and weekly data after that. This is due to the Australian government decision regarding reporting rules. It makes no sense to compare daily data to weekly data. So, all analysis is done on weekly bases.
Data set for new cases has two columns which look similar NEW and NET. Column/variable NEW is used – the number officially reported by authorities. As a result, calculate your own number for total cases. Column NET contains adjusted numbers, you will ignore them as well as column CASES.

**Analysis**
Execute the following steps and present answers for the research questions below.
1. Write an introduction about what type of analysis you plan to execute. Provide a brief data description: what are your data about; how many variables and observations there?
2. Report and discuss distributions of new cases and deaths weekly numbers in five states. 
3. Create a graph to plot the history of COVID-19 in different states. Pay attention that the graph for each state starts on different calendar day as it starts on a day after 100 reported cases. Your graph should start on the week after 1000 cases were reported and then show cumulative weekly numbers as we do a weekly-based analysis. Provide brief comments on the progress of COVID-19.
4. Normalise numbers of new cases by population (see table in the appendix) and plot a calendar-based historical graph of weekly cases. Provide brief comments on similarities and differences.
5. Study a relationship between number of new cases and deaths in five states. 


**Appendix**
The latest numbers for the Australian population from Australian Bureau of Statistics (ABS) – https://www.abs.gov.au/statistics/people/population/national-state-and-territory-population/dec-2022
State	            Population at 31 December 2022 ('000)	      Change over previous year ('000)	      Change over previous year (%)
New South Wales	            8,238.8	                                      138.0	                                  1.7
Victoria	                  6,704.3	                                      137.7	                                  2.1
Queensland	                5,378.3	                                      116.6	                                  2.2
South Australia	            1,834.3	                                       28.5	                                  1.6
Western Australia	          2,825.2	                                       62.7	                                  2.3
Tasmania	                    571.6	                                        2.9	                                  0.5
Northern Territory	          250.1	                                        2.0	                                  0.8
Australian Capital Territory	460.9	                                        8.3	                                  1.8

