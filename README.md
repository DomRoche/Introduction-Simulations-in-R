# Introduction to Simulations in R

## About this work
This work was originally created by [Malika Ihle](https://ox.ukrn.org/people/#MalikaIhle) based on materials from [Joel Pick](https://joelpick.wixsite.com/research), [Hadley Wickham](https://www.yumpu.com/en/document/view/19077330/simulation-hadley-wickham), [Kevin Hallgren](https://doi.org/10.20982/tqmp.09.2.p043), and with large contributions from [James Smith](https://github.com/worcjamessmith).   
It is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

## Prerequisites

* Have R and RStudio installed. If you don't, follow [these instructions](https://malikaihle.github.io/Introduction-RStudio-Git-GitHub/installing_software.html)  
* Know some R basics (e.g. how to select a value in a data.frame, how to create a vector). If you don't, visit the tutorial: <a href="https://www.tutorialspoint.com/r/index.htm" target ="_blank">https://www.tutorialspoint.com/r/index.htm</a>  

## Prior to the session
1) Watch this [30 min introduction to credible research](https://osf.io/xtmek/), which contextualise the importance of simulations for reliable research. 

2) Fork and clone [this repository](https://github.com/MalikaIhle/Introduction-Simulations-in-R) ([here](https://malikaihle.github.io/Collaborative-RStudio-GitHub/) is a reminder on how to fork and clone and what it means). If you have never been introduced to version control system, follow [these instructions](./tutorial_pages/download-repo.md) instead.  

3) *Optional* (to start getting familiarised with the content of the session): Read [Hallgren A. K. 2013. Conducting simulation studies in the R programming environment. Tutor Quant Methods Psychol. ; 9(2): 43–60.](https://doi.org/10.20982/tqmp.09.2.p043) and answer the following 3 questions in your local copy of the [reading sheet](./Hallgren2013/ReadingSheet.md):  
  * describe 6 steps common to all simulations  
  * describe 3 types of simulations use  
  * describe 4 limitations of simulations

## During the session: self-paced workshop
### How it works
The self-paced tutorial (pages linked below) will alternate presentation of concepts and simple exercises for you to try to apply them in R. Each time you see written **YOUR TURN**, switch to your local copy of the exercise script (you can chose between a file <a href="https://github.com/MalikaIhle/Introduction-Simulations-in-R/blob/main/exercise_script_with_solutions.R" target ="_blank">with</a> or <a href="https://github.com/MalikaIhle/Introduction-Simulations-in-R/blob/main/exercise_script_without_solutions.R" target ="_blank">without</a> the solutions depending on e.g. your level of familiarity with R), review the examples if needed, complete the exercise, and check out the proposed answer (which often contains additional tips). Come back to the online tutorial and after finishing one page, you can click 'next' at the bottom to continue. The exercise script contains  code for all the exercises and code that generates the plots that appear in the online tutorial, all in order of appearance in the tutorial.  

It is necessary that you work through the sections of the tutorial in order. Please read the blurbs of each sections below to get an overview of this workshop.
 

### Tutorial
* [Definition](./tutorial_pages/definition.md) - what are simulations?
* [Purpose](./tutorial_pages/purpose.md) - what can we use simulations for?
* [Basic Principles](./tutorial_pages/basic-principles.md) - what do we need to create a simulation?
* [Random Number Generators](./tutorial_pages/random-numbers-generators.md) - how to generate random numbers in R?
* [Repeat](./tutorial_pages/repeat.md) - how to repeat the generation of random numbers multiple times?
* [Setting the seed](./tutorial_pages/seed.md) - how can you generate the same random numbers?
* [Sample size `n`](./tutorial_pages/sample-size-n.md) - how many values should you generate within a simulation?
* [Number of simulations `nrep`](./tutorial_pages/number-of-simulations-nrep.md) - how many repeats of a simulation should you run?
* [Dry rule](./tutorial_pages/dry-rule.md) - how to write your own functions?
* [Simulate to check alpha](./tutorial_pages/check-alpha.md) - write your first simulation and check the rate of false-positive findings.  
* [Simulate to check power](./tutorial_pages/check-power.md) - simulate data to perform a power analysis.  
* [Simulate to prepare a preregistration](./tutorial_pages/simulate-for-preregistration.md) - simulate data to test statistical analyses before preregistering them.  
* [General structure](./tutorial_pages/general-structure.md) - what is the general structure of a simulation?
* [Limitations](./tutorial_pages/limitations.md) - what are the limitations to simulations?
* [Real-life example](./tutorial_pages/real-life-example.md) - what are real life examples of simulations?
* [Additional resources](./tutorial_pages/resources.md) - what resource can help you write your own simulation?

## During the session: personal project
In your local repository, write your own simulation in R to help you prepare the data analyses of your current or next study. When you require help, first push your current work on your GitHub remote (for a reminder on how to do this, see [here](https://malikaihle.github.io/Introduction-RStudio-Git-GitHub/)) for us to be able to access it easily and possibly review and edit your code!  

