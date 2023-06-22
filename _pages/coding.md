---
layout: archive
title: "Coding"
permalink: /coding/
author_profile: true
---

Check out my [main github page](https://github.com/zachporreca) to see some of the coding things I've been working on lately. I really don't think of myself as a coder. However, I do try and be resourceful when I come across unsolved problems in my own research. On occasion this can lead me to some unintentional public good provision. I work almost entirely in R, but I have had to make some forays into Julia and Bash scripts.

## R Package: "lpdid" written with [Alex Cardazzi]https://alexcardazzi.github.io/()
- Implements the Linear Projections Difference-in-Differences estimator of [Dube et al. (2023)](https://www.nber.org/papers/w31184)
- This package can be installed as follows:
   ```
      devtools::install_github("alexCardazzi/lpdid")
    ```
    
 - And then after installation can be called by:
      ```
       library(lpdid)
      ```
      

## R Package: "staggeredSynthDid" (*no longer maintained, better alternatives now exist*)
- Implements the Synthetic Difference-in-Differences estimator of [Arkhangelsky et al. (2021)](https://www.aeaweb.org/articles?id=10.1257/aer.20190159) for staggered treatment adoption settings (see [Porreca (2022)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4015931))
- This package can be installed as follows:
     ```
      devtools::install_github("zachporreca/staggered_adoption_synthdid")
    ```
    
 - And then after installation can be called by:
      ```
       library(staggeredSynthDid)
      ```
      
