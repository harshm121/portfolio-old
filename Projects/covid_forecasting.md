---
title: "COVID-19 Forecasting"
---
<head>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-NB6TYSXY61"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-NB6TYSXY61');
</script>
</head>

<img align="center" src="https://harshm121.github.io/Projects/covid_forecasting.png" alt="Forecasting Example" width="30%">
<br>


Since March-2020, I have been volunteering my free time with a group of amazing people and [Wadhwani AI](https://www.wadhwaniai.org/) to help public health authorities in heavily impacted 
Indian regions to forecast the upcoming burden on health infrastructure and plan mobility restriction policies. We created a framework to forecast the infections in an epidemic using SEIR like epidemiological models and a Bayesian Optimization framework to estimate the parameters.
For forecasts of the infection counts for the next 'k' days, we get less than 10% MAPE error (k=7) for Indian districts.

\[[Extended Abstract](https://dl.acm.org/doi/abs/10.1145/3430984.3431047) published in CODS COMAD 2021\] \[[Preprint](https://www.medrxiv.org/content/10.1101/2020.10.19.20215293v1.full)\] [Full work under review at KDD'21]
