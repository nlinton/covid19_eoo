### End-of-outbreak estimation for COVID-19

This repository contains supplementary materials for the article "Localized end-of-outbreak determination for coronavirus disease 2019 (COVID-19): examples from clusters in Japan"

This study has been accepted for publication by the International Journal of Infectious Diseases (IJID).

---

<b>Objectives</b> End-of-outbreak declarations are an important component of outbreak response asthey indicate that public health and social interventions may be relaxed or lapsed. Thepresent study aimed to assess end-of-outbreak probabilities for clusters of coronavirusdisease 2019 (COVID-19) cases during the first wave of the pandemic in Japan.

<b>Methods</b> We computed a statistical model for localized end-of-outbreak determination that accounted for the reporting delay for new cases. Four clusters representing different social contexts and time points during the epidemic were selected and their end-of-outbreak probabilities were evaluated.

<b>Results</b> The end-of-outbreak determination was most closely tied to outbreak size. Larger outbreaks (accounting for missing onsets and underascertainment of cases) tended toreach the proscribed probability thresholds for end-of-outbreak determination at later times compared to smaller outbreaks. In addition, end-of-outbreak determination wasclosely related to estimates of case dispersion k and the effective reproduction numbe R<sub>e</sub>.

<b>Conclusions</b> When public health measures are effective, lower R<sub>e</sub> (less transmission on average) and larger k (lower risk of superspreading) will be in effect and end-of-outbreak determinations can be declared with greater confidence. This application can help distinguish between local extinction and low levels of transmission, and communicating these end-of-outbreak probabilities helps inform public health decision-making around the appropriate use of resources

### Scripts

[A. Analysis in R](scripts\A.eoo_calculating_the_probabilities.ipynb)

[B. Visualization of the results](scripts\A.eoo_figure1.ipynb)

---

Coded by Natalie M. Linton and Andrei R. Akhmetzhanov using R 4.0.4 and CmdStan 2.26.0 with the package cmdstanr, 2021.
