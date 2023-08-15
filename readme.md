This is a repository that contains the source data and all the code required to reproduce the analysis used for the manuscript Estimating cue rates for animals with silence-burst sound patterns by 
Tiago A. Marques, Sónia Coelho, Ana Isabel Leal


The paper describes a new way to estimate cue rates for scenarios in which animals might present silence-burst sound production patterns. It is illustrated with :bird: Common Chaffinch ($Fringila coellebs$) dataset collected in Companhia das Lezirias, Santarém, Portugal in 2022.

We share two master files:

1. The results in the paper are all produced in "Marquesetal2023cuerate4birdsSuppMat.Rmd". Either compiling it or running all the code in this dynamic report has, as a side effect, to produce the file "results4paper.Rdata"
2. The paper itself is produced by "Marquesetal2023cuerate4birds.Rmd", which at the start of the results loads up the file "results4paper.Rdata" as produced by "Marquesetal2023cuerate4birdsSuppMat.Rmd"

This means that all the results are easily reproducible. 
