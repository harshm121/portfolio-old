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
Indian regions to forecast the upcoming burden on health infrastructure and plan mobility restriction policies. We created an [opensource tool](https://github.com/dsindiavscovid/covid19-india/tree/staging)
to forecast the infections in an epidemic using SEIR like epidemiological models and a Bayesian Optimization framework to estimate the parameters.
For forecasts of the infection counts for the next 'k' days, we get less than 10% MAPE error (k=7) for Indian districts.
