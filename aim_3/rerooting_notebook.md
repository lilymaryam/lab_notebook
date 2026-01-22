# Rerooting viral_usher_trees

## 20260121 status
Currently I have a working version of reroot.smk which I am using to run treetime on all 432 versions of trees. The pipeline was breaking during the rerooting of certain trees which had mutations with ambiguous nucleotides. I am recompiling a newer version of usher which can handle these errors. I am waiting to install a newer version of usher_to_taxonium that has not been merged. 

*To install the latest version of usher (version XXX) I made a conda local build following these steps (https://usher-wiki.readthedocs.io/en/latest/Installation.html). However the current environment.yml file is not working so i used my own (get it and link it) *

## 20260122 status
to follow up on yesterdays status. i have successfully recompiled the newest version of usher but have not noticed a significant change in my reroot pipeline. i will wait to see how we want to proceed with finihsing the run of these trees. 

I will use reroot info to help get more data into my spectrum splits pipeline but there are a few things to square away with measles before i move on to more data. 


