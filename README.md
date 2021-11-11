# A mixture model application in monitoring error message rates for a distributed industrial fleet

https://doi.org/10.5281/zenodo.5675789

This repository includes the material required to replicate the analysis done in the article "A mixture model application in monitoring error message
rates for a distributed industrial fleet".

It includes three files:
1. *printerWeek.RData* file including the data frame printerWeek with 400 printers tracked during 27 weeks. The variables are:
  - **machine_id**, printer unique identification code.
  - **week**, week number at which the data was recorded.
  - **print_time_hours**, printing time by the printer on a week.
  - **n_error**, number of error messages release by the printer on a week.
  - **rate**, raw error message rate (n_error/print_time_hours)
3. *camanRunArticle.Rmd*, R Markdown script with the code required to replicate the article steps on the printerWeek data frame.
4. *camanRunArticle.html*, user-friendly html file obtained from knitting the R Markdown *camanRunArticlelJoQT.Rmd*.
