---
title: "Home"
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


<img style="float:left;padding:10px;"
src="./images/personal-photo.png" alt="profile picture" width="15%">
I am a Data Scientist at [Flipkart](https://www.flipkart.com/) in the Recommendations team supervised by [Dr. Aditya Rachakonda](https://in.linkedin.com/in/adityarachakonda), [Dr. Arnab Bhattacharya](https://www.linkedin.com/in/arnab-bhattacharya-26383573) and previously by [Samik Datta](https://www.linkedin.com/in/samik-datta-7b2a927a/). I work on various Candidate Generation and Ranking problems. Prior to joining Flipkart, I completed my undergrad at IIT Delhi advised by [Dr. Prathosh AP](https://sites.google.com/view/prathosh). 


Since March 2020, I have also been volunteering my time with [DSIndiaVsCovid](http://dsindiavscovid.org/) mentored by [Dr. Srujana Merugu](https://www.linkedin.com/in/srujana-merugu-a7243819/) and [Dr. Alpan Raval](https://www.linkedin.com/in/alpan-raval-36219a2/). There, I work on COVID-19 case count forecasting using SEIR type compartmental epidemiological models and bayesian optimization to estimate parameters of the model. The framework is used to guide public health authorities of various Indian districts to plan for the upcoming burden on healthcare infrastructure. I also worked on a control framework to guide public health agencies in creating a policy schedule to control an epidemic.


Broadly my interest lies in Computer Vision, understanding Deep Learning and Machine Learning (theory as well as it's 'impactful' application). I strongly believe that technology benefits human society and has a lot of potential to improve human lives.


## **Projects**:

<font size="2"> 
<table style="width:100%;">
  <tr>
    <th width="30%"><a href="https://harshm121.github.io/Projects/CTL/"><img src="https://harshm121.github.io/Projects/ctl_example.jpeg" alt="CTL Example" height = "20%"></a></th>
	    <th width="70%"><h3><b><a href="https://harshm121.github.io/Projects/CTL/">Complete The Look</a></b></h3> (work in progress)<br><font size="2.2"><i><h8>Supervised by: <a href = "http://www.facweb.iitkgp.ac.in/~niloy/">Prof. Niloy Ganguly</a> - IIT Kharagpur, <a href="https://www.linkedin.com/in/arnab-bhattacharya-26383573/">Dr. Arnab Bhattacharya</a>, <a href="https://www.linkedin.com/in/adityarachakonda/">Dr. Aditya Rachakonda</a> - Flipkart</h8></i></font> <br>
Recommending fashion-compatible outfits given a 'parent' product and introducing diversity in the outfits generated. [<a href="https://harshm121.github.io/Projects/CTL/">More details here</a>]</th> 
  </tr>
	
  <tr>
    <th width="30%"><img src="https://harshm121.github.io/Projects/boardsnapped.png" alt="Example images" width="100%"></th>
	<th width="70%"><h3><b>boardSnapped</b></h3> <font size="2.2"><i><h8> Supervised by: <a href="https://sites.google.com/view/prathosh">Prof. Prathosh AP</a> - IIT Delhi </h8></i></font><br>
	There are a lot of recorded lectures on the internet, but the lectures are usually too long and slow and it is difficult to skim through a video like one would do in notes. We formulated this task to a Machine Learnin task of finding certain key frames from an educational video (NPTEL Videos) which capture all the written content in a video. Thus 1 one hour video can be successfully summarized in about 10 images. [<a href="https://docs.google.com/presentation/d/1hnYlk-_ie_55itjfKPlbFFm5x9woRM1kMJZJNiyOV2I/edit?usp=sharing">Presentation</a>]
</th> 
  </tr>
  
<tr>
    <th width="30%"><img src="https://harshm121.github.io/Projects/skinseg.png" alt="Skin segmentation example" width = "100%"></th>
	  <th width="70%"><h3><b>Skin Segmentation using NIR Images</b></h3> <font size="2.2"><i><h8> Supervised by: <a href="https://sites.google.com/view/prathosh">Prof. Prathosh AP</a> - IIT Delhi </h8></i></font><br>
The aim of the project was to segment human skin out of Near Infrared Images. Skin segmentation from RGB images is a well studied problem but since many night vision cameras use infrared, segmenting skin from infra red images can be useful. This requires a lot of annotated data which is not available in large amounts. However, RGB images with skin annotations are available abunduntly. Hence to solve the problem of data availability, we first trained a RGB to NIR Transformation using pix2pix type conditional GAN and then trained a skin segmentation on RGB converted to NIR images. </th> 
  </tr>
  
  <tr>
    <th width="30%"><a href="https://harshm121.github.io/Projects/covid_forecasting"><img src="https://harshm121.github.io/Projects/covid_forecasting.png" alt="Forecasting Example" width = "100%"></a></th>
	  <th width="70%"><h3><b><a href="https://harshm121.github.io/Projects/covid_forecasting">COVID-19 Forecasting</a></b></h3> <font size="2.2"><i><h8> Supervised by: <a href="https://www.linkedin.com/in/srujana-merugu-a7243819/">Dr. Srujana Merugu</a>, <a href="https://www.linkedin.com/in/alpan-raval-36219a2/">Dr. Alpan Raval</a> - Wadhwani AI, <a href="https://in.linkedin.com/in/mohitkum">Dr. Mohit Kumar</a> - Udaan</h8></i></font><br>
Created a Machine Learning framework to forecast the upcoming burden on health infrastructure and help public health authorities in planning policies. [<a href="https://harshm121.github.io/Projects/covid_forecasting">More details here</a>] [<a href="https://www.medrxiv.org/content/10.1101/2020.10.19.20215293v1">Extended Abstract</a> published in CoDS-COMAD'21]</th> 
  </tr>
	
	
  <tr>
    <th width="30%"><a href="https://harshm121.github.io/Projects/cosir/"><img src="https://harshm121.github.io/Projects/cosir.png" alt="CoSIR Model" width="100%"></a></th>
	<th width="70%"><h3><b><a href="https://harshm121.github.io/Projects/cosir/">Controlling an Epidemic</a></b></h3> <font size="2.2"><i><h8> Supervised by:  <a href="https://www.linkedin.com/in/srujana-merugu-a7243819/">Dr. Srujana Merugu</a> </h8></i></font><br>
Proposed an analytical framework to help create a mobility restriction policy schedule to control an epidemic to a desired level.[<a href="https://harshm121.github.io/Projects/cosir/">More details here</a>] [<a href="https://www.medrxiv.org/content/10.1101/2020.11.10.20211995v1">preprint</a>] </th> 
  </tr>
  
	
  <tr>
    <th width="30%"><a href="https://harshm121.github.io/Projects/supermart/"><img src="https://harshm121.github.io/Projects/supermart.png" alt="supermart sugar example" height="80%"></a></th>
	<th width="70%"><h3><b><a href="https://harshm121.github.io/Projects/supermart/">Audience Creation for Consumables</a></b></h3> <font size="2.2"><i><h8> Supervised by: <a href="https://www.linkedin.com/in/samik-datta-7b2a927a/">Samik Datta</a> - Flipkart</h8></i></font> <br>
Creating an audience set for a store at Flipkart's Online Grocery marketplace, called Supermart, based on puchase probability by modelling a user's purchase behaviour and periodicity in buying consumables. [<a href="https://harshm121.github.io/Projects/supermart/">More details here</a>] [<a href="https://arxiv.org/abs/2011.08575">Preprint</a>]</th> 
  </tr>

  <tr>
    <th width="30%"><img src="https://harshm121.github.io/Projects/reco.png" alt="Recommendation word cloud" height="80%"></th>
	<th width="70%"><h3><b>Candidate Generation and Ranking</b></h3> <font size="2.2"><i><h8>Supervised by: <a href="https://www.linkedin.com/in/samik-datta-7b2a927a/">Samik Datta</a>, <a href="https://www.linkedin.com/in/adityarachakonda/">Dr. Aditya Rachakonda</a> - Flipkart</h8></i> </font><br>
		Customized <b>Bayesian Personalised Ranking</b> based Matrix Factorisation framework for Flipkart homepage recommendation (improvement in clicks by 2 bps on Flipkart homepage, currently in larger A/B testing phase) and designed multiple Lamda MART & LR based rankers for Flipkart home and product page.</th> 
  </tr>
  
</table>
</font>

## **Publications**:
**\* Equal Contribution** 

(1) Shreyas S\*, **Harsh Maheshwari\***, Avijit Saha\*, Samik Datta\*, Shashank Jain, Disha Makhija, Anuj Nagpal, Sneha Shukla, Suyash S, "Audience Creation for Consumables - Simple and Scalable Precision Merchandising for a Growing Marketplace", Under Review at ICDE'21,  \[[preprint](https://arxiv.org/abs/2011.08575)\]
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Consumable categories, such as grocery and fast-moving consumer goods, are quintessential to the growth of e-commerce marketplaces in developing countries. In this work, we present the design and implementation of a precision merchandising system, which creates audience sets from over 10 million consumers and is deployed at Flipkart Supermart, one of the largest online grocery stores in India. We employ temporal point process to model the latent periodicity and mutual-excitation in the purchase dynamics of consumables. Further, we develop a likelihood-free estimation procedure that is robust against data sparsity, censure and noise typical of a growing marketplace. Lastly, we scale the inference by quantizing the triggering kernels and exploiting sparse matrix-vector multiplication primitive available on a commercial distributed linear algebra backend. In operation spanning more than a year, we have witnessed a consistent increase in click-through rate in the range of 25-70% for banner-based merchandising in the storefront, and in the range of 12-26% for push notification-based campaigns.
</i>
</p>
</div>
</details>
<br>

(2) **Harsh Maheshwari\***, Shreyas Shetty\*, Nayana Bannur, Srujana Merugu, "CoSIR: Managing and Epidemic via Optimal Adaptive Control of Transmission Policy" \[[preprint](https://www.medrxiv.org/content/10.1101/2020.11.10.20211995v1)\]
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Shaping an epidemic with an adaptive contact restriction policy that balances the disease and socioeconomic impact has been the holy grail during the COVID-19 pandemic. Most of the existing work on epidemiological models focuses on scenario-based forecasting via simulation but techniques for explicit control of epidemics via an analytical framework are largely missing. In this paper, we consider the problem of determining the optimal policy for transmission control assuming SIR dynamics, which is the most widely used epidemiological paradigm. We first demonstrate that the SIR model with infectious patients and susceptible contacts (i.e., product of transmission rate and susceptible population) interpreted as predators and prey respectively reduces to a Lotka-Volterra (LV) predator-prey model. The modified SIR system (LVSIR) has a stable equilibrium point, an energy conservation property, and exhibits bounded cyclic behaviour similar to an LV system. This mapping permits a theoretical analysis of the control problem supporting some of the recent simulation-based studies that point to the benefits of periodic interventions. We use a control-Lyapunov approach to design adaptive control policies (CoSIR) to nudge the SIR model to the desired equilibrium that permits ready extensions to richer compartmental models. We also describe a practical implementation of this transmission control method by approximating the ideal control with a finite, but a time-varying set of restriction levels and provide simulation results to demonstrate its efficacy.
</i>
</p>
</div>
</details>
<br>

(3) Nayana Bannur, **Harsh Maheshwari**, Sansiddh Jain, Shreyas Shetty, Srujana Merugu, Alpan Raval, "Adaptive COVID-19 Forecasting via Bayesian Optimization", in CoDS-COMAD 2021 \[[paper](https://doi.org/10.1101/2020.10.19.20215293)\]
<details><summary>Abstract</summary>
<div>
<p style="background-color:#ffffcc;"> 
<i>Accurate forecasts of infections for localized regions are valuable for policy making and medical capacity planning. Existing compartmental and agent-based models for epidemiological forecasting employ static parameter choices and cannot be readily contextualized, while adaptive solutions focus primarily on the reproduction number. In the current work, we propose a novel model-agnostic Bayesian optimization approach for learning model parameters from observed data that generalizes to multiple application-specific fidelity criteria. Empirical results demonstrate the efficacy of the proposed approach with SEIR-like compartmental models on COVID-19 case forecasting tasks. A city-level forecasting system based on this approach is being used for COVID-19 response in a few highly impacted Indian cities.</i>
</p>
</div>
</details>
<br>

**Personal Interests:** I like watching and reading biographies and documentaries. I also enjoy surfing YouTube which I feel is an extremely far reaching and impactful platform. I have personally found alot of content which intrigues me. Philosophy and Technology are two domains I find very engaging and am always up for discussing them at lengths.



**Contact**: Contact me at [harshm121@gmail.com](mailto:harshm121@gmail.com) or using any social media links above. 

