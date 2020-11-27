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
<figure>
<img style="margin-left: auto; display: block; margin-right: auto;" src="https://harshm121.github.io/Projects/ctl_example.jpeg" alt="CTL example" width="30%">
<br>
<figcaption>An example of Complete the look recommendations (representative image)</figcaption>
</figure>

For product page recommendations for lifestyle product, recommending fashion-compatible products is a great way to inspire users and help them in their purchase journey. Below is the formal problem statement and the work already done (and currently in progress) for Flipkart's Complete The Look

**Problem Statement**: To generate 'fashion-wise' **compatible** and **diverse** outfits for **Indian Users** given a parent product belonging to the parent category and a template (list of categories, e.g.: Parent Category: Tshirts, Child Categories: Jeans, Shoes, Watch)


**Work Description**: To solve the problem of fashion recommenation, we started with the problem of modelling fashion-compatiblily. For this, I implemented state-of-the-art methods by Amazon and ASOS.com  and trained on the publicly available Polyvore-fashion (UK based website) dataset. After looking at the generated outfits, we realised that the outfits are heavily color matched (preferred in UK) which is not desirable for Indian context. This gave us a unique opportunity to solve the problem for an Indian context with limited data on Indian compatible outfits. 
We are also working on introducing diversity in the outfits generate to meet the preferences of diverse set of users. To introduce **diversity** we are using techniques like **Determinantal point process** and **Diverse Beam Search**. 

**Work Description**: Fashion-compatible outfit generation is a well studied problem in the computer vision community. The most popular dataset, [Polyvore Dataset](https://arxiv.org/pdf/1803.09196.pdf) was collected by users majorly from the western world. After working on the data, we realised that the fashion-compatibility learnt from Polyvore data would be biased towards preferences of the western world and may not be suitable for Indian users. Figure 1 shows one of the many outfits from the Polyvore Dataset. As visible, the outfi is biased towards color based matching which is usually not preferred in India. 

<figure>
<img src="https://harshm121.github.io/Projects/polyvore_example.jpeg" alt="Polyvore example" width="15%">
<br>
<figcaption>Figure 1: One of the outfits present in Polyvore Dataset</figcaption>
</figure>

We are trying to solve fashion-compatibility for regions which might not have a lot of data. We found two unique problems not addressed in the existing literature, the first being differences in fashion compatibility across regions, which motivated the following question: *Can we learn fashion-compatibility as the combination of region-dependent and region-independent components?* The second issue that we want to address pertains to nuanced user-related preferences: *How can we generate diverse fashion compatible outfits to account for user preferences?*



