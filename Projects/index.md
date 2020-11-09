---
title: "Projects"
---
<head>
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-2QHSF0Q5FG"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-2QHSF0Q5FG');
</script>
</head>

## Projects

1. Data Scientist, [Flipkart](https://www.flipkart.com/) (Supervised by Dr. Arnab Bhattacharya, Dr. Aditya Rachakonda, Samik Datta) \

	-**Complete The Look**,	(Dr. Niloy Ganguly - IIT Kharagpur, Dr. Arnab Bhattacharya)
		-*Problem Statement:* To generate 'fashion-wise' compatible outfits given a parent product
		-*Work Description:* To solve the problem of fashion recommenation, we started with the problem of modelling fashion-compatiblily. For this, I implemented state-of-the-art CNN architectures by Amazon (CVPR'20) and ASOS.com (KDD Fashion'18) on the publicly available Polyvore-fashion (UK based website) dataset. After looking at the generated outfits, we realised that the outfits are heavily color matched (preferred in UK) which is not desirable for Indian context. This initiated the problem of introducing diversity in outfit generation. We realised that diversity could be both, within an outfit, and across different outfits for a parent product. 
		
	-**Audience Creation for Consumables**,	(Samik Datta)
		-*Problem Statement:* Given a store and past purchases of the users, create an audience of required size ordered with the probabilty of puchase
		-*Work Description:* Consumables (grocery products like Sugar, Ketchup) have periodicity in their purchases. We tried to model this periodicity with a temporal point process and evaluated the method against state of the art baselines using carefully designed experiments and online A\B tests. The technical report is under review at ICDE 2021 Industrial track. [prepreint: to be released soon]
		
	-**Candidate Generation and Ranking**, (Samik Datta, Dr. Adtiya Rachakonda)
		-*Work Description:* Customized **Bayesian Personalised Ranking** based Matrix Factorisation framework for Flipkart homepage recommendation (improvement in clicks by 2 bps on Flipkart homepage, currently in larger A/B testing phase) and designed multiple Lamda MART & LR based rankers for Flipkart home and product page.
	

1. Skin Segmentation (Dr. Prathosh AP, IIT Delhi):
	- The aim of the project is to segment human skin out of Near Infrared Images. Skin segmentation is a solved problem for RGB images but since many night vision cameras use infrared, segmenting images can be useful from infra red images. The problem we faced was to generate data as the data labelling required intense human intelligence. 
	To work around the problem of data, we are trying to use conditional GANs to convert a given RGB image to an NIR image. With this we could use the huge datasets available with RGB images and their skin segmented mask.

2. BoardSnapped (Dr. Prathosh AP, IIT Delhi)


