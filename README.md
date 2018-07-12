# nu_openpolicing <br>
This is a repo for a hyper-local analysis of [Stanford's Open Policing](https://openpolicing.stanford.edu/) data applied to Evanston, IL.
## Data <br>
General data from IL is from 2004-2015--a HUGE, very complete dataset. <br>
It is available as a .tar.gz [here](https://stacks.stanford.edu/file/druid:py883nd2578/IL-clean.csv.gz) or as a .zip [here](https://northwestern.box.com/s/ea7puk3405w32f9h4rvaswl48qx4ktrf) (NU Box folder/file). <br>
There is also [Census data] (https://stacks.stanford.edu/file/druid:py883nd2578/census-clean.csv.gz) and [Polic Public Contact Survey data](https://stacks.stanford.edu/file/druid:py883nd2578/ppcs.tsv)--both of which are .tar.gz right now (will upload as .zip to Box soon).
## Approach <br>
There are at least two initial thrusts to analysis: <br>
(1) 'Port' the [R code](https://github.com/5harad/openpolicing/blob/master/src/recreate_results_in_paper.R) used in the [working paper](https://northwestern.box.com/s/ea7puk3405w32f9h4rvaswl48qx4ktrf) from Stanford to Python <br>
(2) Filter the data to focus on Evanston <br>
Ideally, (1), could be done separately from (2), and then the methods from (1) can be reapplied to (2). <br>
Logically, we will try to mimic the the file structure from Stanford's [github](https://github.com/5harad/openpolicing) for the national project
## Goal <br>
Build some nice visualizations of the data to make some statements about potential disparities in traffic policing by race/Ward in Evanston, and push them to Evanston's Open Data [Community](https://cityofevanston.data.socrata.com/browse?provenance=community) web portal
