# R Clifford Attractors
## Description


This  [CliffordAttractors R script](./apps/CliffordAttractors.R) have been created by Antonio Sánchez Chinchón.

You can read his blog post about it [here](https://fronkonstin.com/2017/11/07/drawing-10-million-points-with-ggplot-clifford-attractors/)

You can find also plenty of others amazing R Scripts on Antonio Sánchez Chinchón website : [https://fronkonstin.com/](https://fronkonstin.com/)

To run this R Script, we start on the r-base docker image and we added some libraries and needed dependencies.

You can see the corresponding [Dockerfile](./apps/Dockerfile). This docker image has been pushed into this docker repository [iexechub/r-clifford-attractors](https://hub.docker.com/r/iexechub/r-clifford-attractors).

## [Dapp params](./iexec.js)

4 parameters a,b,c,d are needed for the CliffordAttractors Script.

The command line with the 4 parameters and the docker image to use must be configure into the [iexec.js](./iexec.js).

##  Result
Result with 

a=-1.24458046630025

b=-1.25191834103316

c=-1.81590817030519

d=-1.90866735205054

![Clifford.png](./apps/Clifford.png)

Try yourself and play with a,b,c,d parameters values.







