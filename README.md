# Example project that includes a make file   
2019-08-20

# Overview:

I'm exploring make because I'm looking for a good method of tracking file dependencies and pushing updating changes automatically. I think that's pretty much what Make was created to do. This is just a baby example I'm using to better understand:

* How does make work?   
* Does make work well with Rmd files?   
* Does make work well with version control?   
* Does make make it easier to visualize relationships between files (i.e. for pathfinder)?   

# Other solutions I've tried:

* [Drake](https://github.com/ropensci/drake).    
    - Drake seems like it is more complex than needed for problems I'm trying to solve.    
    - I still can't get the graphs to work in Drake.   
    - Drake doesn't seem conducive to working interactively with notebooks.    
    - I don't want to have to tell my solution ahead of time what I'm going to do. I want to just do things, then have my solution keep track of what I did and what other parts of my process may be affected.