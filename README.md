# nu_openpolicing <br>
Exploring and visualizing  bias in policing Illinois ; initial data based on [Stanford's Open Policing](https://openpolicing.stanford.edu/); we are also looking at exploring/analyzing Invisible Institute's Chicago [Citizen's Police Data](https://github.com/invinst/chicago-police-data), but, at first glance, this is somehwat more segmented (and will need to be unified?)
## Data <br>
Stanford's Open Policing (SOP) data from IL is from 2004-2015--a HUGE, very complete dataset. <br>
It is available as a .tar.gz [here](https://stacks.stanford.edu/file/druid:py883nd2578/IL-clean.csv.gz) or as a .zip [here](https://northwestern.box.com/s/ea7puk3405w32f9h4rvaswl48qx4ktrf) (NU Box folder/file). <br>
There is also [Census data](https://stacks.stanford.edu/file/druid:py883nd2578/census-clean.csv.gz) and [Polic Public Contact Survey data](https://stacks.stanford.edu/file/druid:py883nd2578/ppcs.tsv).
## Goal <br>
(A) Examining what factors affect if a driver in Illinois has their car searched for contraband
(B) Build some nice visualizations of the data to make some statements about potential disparities in traffic policing in IL + Chicago; perhaps push to [Open Data Bits](https://opendatabits.com/about/)?
## Approach <br>
For (A), some preliminary analysis has already been done in an iPython notebook<br>
For (B) there are at least two initial thrusts to analysis: <br>
(1) 'Port' the [R code](https://github.com/5harad/openpolicing/blob/master/src/recreate_results_in_paper.R) used in the [working paper](https://northwestern.box.com/s/ea7puk3405w32f9h4rvaswl48qx4ktrf) from Stanford to Python <br>
(2) Filter the data to focus on IL or Chicago (or Evanston) <br>
Ideally, (1), could be done separately from (2), and then the methods from (1) can be reapplied to (2). <br>
Logically, we will try to mimic the the file structure from Stanford's [github for the national project](https://github.com/5harad/openpolicing) <br>
A demo for different visualization tools with DataFrame.plot APIs and Voyager has been added in /dotplot and /voyager, respectively
