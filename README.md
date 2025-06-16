# NFHS Data

Structured data from the [National Federation of State High School Associations annual participation surveys](https://www.nfhs.org/sports-resource-content/high-school-participation-survey-archive/). The NFHS produces annual surveys measuring participation in high school sports in every state and the District of Columbia, including breakdowns of the number of schools and participants by sex. Each folder in this repository contains the source PDF and CSV datafiles of figures from the survey. Those CSV files include:

* totals_{year}.csv - overall numbers of schools and participants by sport and sex, including adaptive sports
* boys_schools_{year}.csv - top 10 boys' sports by number of schools
* boys_participants_{year}.csv - top 10 boys' sports by number of participants
* girls_schools_{year}.csv - top 10 girls' sports by number of schools
* girls_participants_{year}.csv - top 10 girls' sports by number of participants
* boys_by_state_{year}.csv - number of schools and participants for boys' sports, by state
* girls_by_state_{year}.csv - number of schools and participants for girls' sports, by state

In addition, the most recent year contains a `historical.csv` file that has overall boys and girls participation figures for every year since 1971-72, except for 2019-20 and 2020-21, due to the Covid-19 pandemic.