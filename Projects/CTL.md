---
title: "Complete The Look"
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

<img align="center" src="https://harshm121.github.io/Projects/ctl_example.jpeg" alt="CTL example" width="30%">
<br>
<em>An example of Complete the look recommendations (representative image)</em>


For product page recommendations for lifestyle product, recommending fashion-compatible products is a great way to inspire users and help them in their purchase journey. Below is the formal problem statement and the work already done (and currently in progress) for Flipkart's Complete The Look

**Problem Statement**: To generate 'fashion-wise' **compatible** and **diverse** outfits given a parent product belonging to the parent category and a template (list of categories, e.g.: Parent Category: Tshirts, Child Categories: Jeans, Shoes, Watch)


**Work Description**: To solve the problem of fashion recommenation, we started with the problem of modelling fashion-compatiblily. For this, I implemented state-of-the-art methods by Amazon (CVPR'20) and ASOS.com (KDD Fashion'18) and trained on the publicly available Polyvore-fashion (UK based website) dataset. After looking at the generated outfits, we realised that the outfits are heavily color matched (preferred in UK) which is not desirable for Indian context. This gave us a unique opportunity to solve the problem for an Indian context with limited data on Indian compatible outfits. 
We are also working on introducing diversity in the outfits generate to meet the preferences of diverse set of users. To introduce **diversity** we are using techniques like **Determinantal point process** and **Diverse Beam Search**. 
