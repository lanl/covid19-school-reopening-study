# COVID-19 School Reopening Study Output

## Spreadsheets

### Fewer vs. More Spreadsheets

Per the phase guidelines released in *[Opening Up America Again](https://www.whitehouse.gov/priorities/covid-19/)*, we modeled two scenarios: "Fewer Open Workplaces", similar to Phase 2 of *Opening Up America Again*, and "More Open Workplaces", similar to Phase 3. These two scenarios describe different levels of in-person workplace assumptions. Specifically, Fewer Open Workplaces encourages telework whenever possible and feasible with business operations as well as limited onsite operations for a small set of businesses. More Open Workplaces assumes staffing of additional worksites with an expanded number of onsite workers. An example is a retail business may be open to 25% customer capacity as per Phase 2 recommendations, and the [NAICS](https://www.census.gov/eos/www/naics/) industry percentage of employees working onsite is 50% (in order to accommodate the workers necessary for the operation of the business) for Fewer Open Workplaces. For More Open Workplaces, this business may have the opportunity to have a 50% customer capacity, and the percentage of employees needed would increase to 75%. For a comparison across intervention approaches, we also use a pre-pandemic behavior scenario, which assumes that all businesses are open with no capacity or social distancing restrictions.

Despite "fewer" being grammatically correct, the spreadsheets use the word "less". We use "fewer" throughout this document.

### `<state name> {Less, More} Workplaces.xlsx`

For a given state (specified in the file name), these files summarize:

* The total number of COVID-19 cases in each scenario broken up by age.
* The total number of hospitalizations in each scenario broken up by age.
* The total number of people in an ICU in each scenario broken up by age.
* The total number of people on a ventilator in each scenario broken up by age.
* The total number of deaths in each scenario broken up by age.

These files are made available for both the fewer and more open workplaces scenarios.

### Scenarios

* **Pre-Pandemic Behavior Cases** - Total cases for no mitigations, all businesses completely open (i.e., 100% enrollment with no social distancing in place).
* **Baseline Cases** - Total cases for all students physically in school with some social distancing (i.e., 100% enrollment).
* **Offsite Cases** - Total cases for no students physically in school.
* **40% POL SD 2Days Cases** - Total cases for two non-overlapping cohorts of students - 40% of the students attend for two days/week (Mon/Tue) and the other 40% attend for two days (Thu/Fri). Wednesday off for disinfection.
* **40% POL SD Week Cases** - Total cases for two non-overlapping cohorts of students - 40% of the students attend one week and the other 40% attend the next week.
* **80% OL SD Cases** - Total cases for all enrolled students physically in school.
* **Offsite Cases Averted** - Total cases averted when compared to the baseline scenario for no students physically in school.
* **40% POL SD 2Days Cases Averted** - Total cases averted when compared to the baseline scenario for two non-overlapping cohorts of students - 40% of the students attend for two days/week (Mon/Tue) and the other 40% attend for two days (Thu/Fri). Wednesday off for disinfection.
* **40% POL SD Week Cases Averted** - Total cases averted when compared to the baseline scenario for two non-overlapping cohorts of students - 40% of the students attend one week and the other 40% attend the next week.
* **80% OL SD Cases Averted** - Total cases averted when compared to the baseline scenario for all enrolled students physically in school.

### `CAR and Cases per 100K.xlsx`

This file summarizes data for each state into a single spreadsheet:

* Clinical attack rate (CAR)
* Cases per 100K
* Total cases
* State population

### `Less Workplaces Epi Curve Data.xlsx`

This file contains daily time series of cases for each state for each scenario for the fewer open workplaces scenario.

### `More Workplaces Epi Curve Data.xlsx`

This file contains daily time series of cases for each state for each scenario for the more open workplaces scenario.

## Maps and Movies

This directory contains maps and movies created from the scenarios described above.

* Movies show new cases per day per 100K by county for each scenario.
* Maps show the cumulative number of cases per 100K by county over the duration of our simulation for each scenario.

## Authors

* Timothy C. Germann
* Manhong Z. Smith
* Lori Dauelsberg
* Geoffrey Fairchild
* Terece L. Turton
* Morgan E. Gorris
* Chrysm Watson Ross
* James P. Ahrens
* Daniel D. Hemphill
* Carrie Manore
* Sara Y. Del Valle

## LA-UR

This repository is approved for public release and is assigned number LA-UR-21-20469.
