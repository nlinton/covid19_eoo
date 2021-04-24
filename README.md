# Localized end-of-outbreak determination for coronavirus disease 2019 (COVID-19): examples from clusters in Japan

## Abstract
<b>Objectives</b> End-of-outbreak declarations are an important component of outbreak response as they indicate that public health and social interventions may be relaxed or lapsed. The present study aimed to assess end-of-outbreak probabilities for clusters of coronavirus disease 2019 (COVID-19) cases during the first wave of the pandemic in Japan.

<b>Methods</b> We computed a statistical model for localized end-of-outbreak determination that accounted for the reporting delay for new cases. Four clusters representing different social contexts and time points during the epidemic were selected and their end-of-outbreak probabilities were evaluated.

<b>Results</b> The end-of-outbreak determination was most closely tied to outbreak size. Larger outbreaks (accounting for missing onsets and underascertainment of cases) tended to reach the proscribed probability thresholds for end-of-outbreak determination at later times compared to smaller outbreaks. In addition, end-of-outbreak determination was closely related to estimates of case dispersion k and the effective reproduction number R<sub>e</sub>.

<b>Conclusions</b> When public health measures are effective, lower R<sub>e</sub> (less transmission on average) and larger k (lower risk of superspreading) will be in effect and end-of-outbreak determinations can be declared with greater confidence. This application can help distinguish between local extinction and low levels of transmission, and communicating these end-of-outbreak probabilities helps inform public health decision-making around the appropriate use of resources

Published in IJID: https://www.sciencedirect.com/science/article/pii/S1201971221001922

## Code

[A. Analysis in R and CmdStan](https://nbviewer.jupyter.org/github/nlinton/covid19_eoo/tree/master/scripts/A.eoo_calculating_the_probabilities.ipynb)

[B. Visualization of the results](https://nbviewer.jupyter.org/github/nlinton/covid19_eoo/tree/master/scripts/B.eoo_figure1.ipynb)

## Core software and packages
* R 4.0.4
* CmdStan 2.26.0
* cmdstanr 0.3.0


## Authors
Name|Twitter|Github|
---|---|---|
Natalie M. Linton|[@nlinton_epi](https://twitter.com/nlinton_epi)|[nlinton](https://github.com/nlinton/)
Andrei R. Akhmetzhanov|[@aakhmetz](https://twitter.com/aakhmetz)|[aakhmetz](https://github.com/aakhmetz/)
Hiroshi Nishiura|[@nishiurah](https://twitter.com/nishiurah/)||
