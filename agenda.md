
# Developers Workshop 2017

__Date__

August 14-18, 2017

__Location__

[International Council for the Exploration of the Sea (ICES)](http://ices.dk)

H.C. Andersens Boulevard 44-46, Copenhagen
([map](https://www.google.dk/maps/place/ICES/@55.671484,12.5734843,17z/data=!3m1!4b1!4m5!3m4!1s0x46525314a3d57cd7:0x115cb810f9d78370!8m2!3d55.671484!4d12.575673?hl=en))

## Description

__Objectives__

__Presentations__

* Helen Ogden
  * Checking the quality of Laplace-approximate inference

__Possible Topics__

* Discuss with TMB developers to add spatial-temporal tools into ADMB (Requested by Mark Maunder)

* Presentation on TINY_AD (proposed by John Sibert)
  * Using TINY_AD to improve ADMB code base
  * Using TINY_AD to improve existing ADMB applications - possible breakout session

* Improvements to MCMC functionality
  * Demonstrate stable versions of NUTS for TMB and ADMB and how they compare to Stan
  * What can go wrong and how to fix it (focus on stock assessments), try on some real models
  * Discuss next steps (if any)

* Priotizing avenues for statistical improvement
  * Variational methods
  * Using MCMC instead of Importance Sampling with fixed seed to replace Laplace approximation
  * Incorporating generalized hypergeometric function (for N-mixture model)

* Prioritizing computational improvements
  * Low-memory bias-correction
  * GPU testing for different operating systems

* Improve TMB documentation [Book](http://kaskr.github.io/adcomp/_book/Tutorial.html)

* Improve TMB Rstudio integration
  - Easier setup. Continue `setupRstudio` branch.
  - Make the static code analyzer work (use `.rs.setClangDiagnostics(2)` to debug it).

## Schedule

__Monday__

__Time__ | __Activity__ | __Notes__
--- | --- | ---
10am | Opening ceremony, Biscay Room (4th floor)
Noon | Lunch
1pm | Helen Ogden's presentation
3pm | Breakout groups
5pm | Done

__Tuesday__

__Time__ | __Activity__ | __Notes__
--- | --- | ---
9am | Start
Noon | Lunch
5pm | Done

* Presentation: Kasper Kristensen, “Recent updates to TMB”
* Presentation: Kasper Kristensen, “TINY_AD in TMB and ADMB”
* Presentation: Kasper Kristensen, “How to add user contributed C++ files”
* Discuss topics to cover in videos.
* Discuss training courses.

__Wednesday__

__Time__ | __Activity__ | __Notes__
--- | --- | ---
9am | Stuff
Noon | Lunch
5pm | Done

__Thursday__

__Time__ | __Activity__ | __Notes__
--- | --- | ---
9am | Stuff
Noon | Lunch
Afternoon | Foundation Meeting
5pm | Done

* Discuss potential working groups that could be funded through [rOpenSci](https://www.r-bloggers.com/announcing-the-ropensci-fellowships-program/)

__Friday__

__Time__ | __Activity__ | __Notes__
--- | --- | ---
9am | Stuff
Noon | Lunch
5pm | Done

## Participants

__Name__ | __Attendance__ | __Affiliation__ | __Notes__
--- | --- | --- | ---
Anders Nielsen | in person | Technical University of Denmark | TMB and glmmTMB developer
Andrea Havron | in person | University of Auckland, NZ
Arni Magnusson | in person | ICES Secretariat, Denmark | ADMB Foundation President
Casper Berg | in person | Technical University of Denmark | TMB and glmmTMB developer
Chris Grandin | in person | DFO Pacific Biological Station, Canada
Gavin Fay | in person | University of Massachusetts
Hans Skaug | in person | University of Bergen, Norway
Helen Ogden | in person | University of Southampton, UK
Johnoel Ancheta | in person | University of Hawaii | ADMB Core Developer
Kasper Kristensen | in person | Technical University of Denmark | TMB and glmmTMB developer
Mollie Brooks | in person | Technical University of Denmark | ADMB Foundation Secretary

__Name__ | __Attendance__ | __Affiliation__ | __Notes__
--- | --- | --- | ---
Allan Hicks | remote | Intl Pacific Halibut Commission | ADMB Foundation Treasurer
Athol Whitten | ? | Mezo Research, Sydney
Christoffer Albertsen | ? | Technical University of Denmark
Cole Monnahan | remote | University of Washington | MCMC methods developer
Dave Fournier | ? | Otter Research | ADMB founder
Jim Thorson | ? | NOAA
John Sibert | remote | ADMB Project, JIMAR, University of Hawaii | ADMB founder
Jim Ianelli | remote | ADMB Project, NOAA | ADMB fanboy
Uffe Thygesen | ? | Technical University of Denmark
