# BLAST-Mapper
An iPython notebook containing code for plotting BLAST hit position across multiple genomes using the [Bokeh](http://bokeh.pydata.org/en/latest/) plotting library.

**Overview:**

  1. Sorts chromsomes/plasmids of the organism by length.
  2. Ends each chromosome with a ```⊣```
  3. Plots BLAST hits to each chromosome/plasmid (can colour code hits by groups)
  
  Example publication figure (from Bergstrand et al. 2016): 
  
  ![Example Publcation Image](https://raw.githubusercontent.com/LeeBergstrand/BLAST-Mapper/master/F4.large.jpg)

This notebook is basically a demo and needs to be turned into a proper library.

**Known Issues:**

1. This software was built usings an old version of Bokeh and iPython notebooks. Bokeh has had drastic API changes since this was implemented.
2. The software current gets its data from a precomputed SQLite database.
