# Statisticsandgraphs-orderedcategoriesandvariables
Statisticsandgraphs—orderedcategoriesandvariables
The frequency distribution produced by tab1 is probably the most useful way to describe the distribution of an ordered categorical variable. We can see that it is fairly symmetrically distributed around the mode of moderate, with somewhat more people describing themselves as conservative rather than liberal.
* Statisticsandgraphs—orderedcategoriesandvariables
* We use median and mean to measure central tendency for ordered categories and variables. 
use descriptive_gss.dta, clear

* run the command numlabel all,add so that both the numbers and the value labels are shown
numlabel _all, add
tab1 polviews
summarize polviews, detail
