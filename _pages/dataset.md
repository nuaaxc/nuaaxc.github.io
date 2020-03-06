---
title: "Opinion Fraud Detection"
permalink: /datasets/
author_profile: true
---

## Overview
With the growing availability of review services at online stores or opinion sharing websites, consumer-generated reviews have become an indispensable part of online shopping. Nowadays online shoppers will not purchase a product without reading the reviews. However, many of the reviews they've read may not be that genuine as expected. It has been found that some (paid) review writers have engaged in the activities of posting fraudulent reviews, to promote/defame some specified products for their best interests.

## Amazon.cn Dataset [(Click here to download)](https://drive.google.com/folderview?id=0B9sH-hWFN-5zSzFKWTNfUWVrSEU&usp=sharing){:target="_blank"}
This dataset contains consumer reviews with rich attributes from [Amazon.cn](https://www.amazon.cn/) (Amazon in China), which contains:
* 1,205,125 reviews 
* 645,072 reviewers 
* 136,785 products

Each review has ten attributes: 
* reviewer id
* product id
* username
* rating
* timestamp
* review title
* review content
* number of helpfulness votes
* number of overall votes
* product category

The dataset also contains **annotated collusive spammers ("colluders")**, who form coordinated groups to write fake reviews together for particular targeted products. We have identified 3,118 non-colluders and 1,937 colluders in total.

We encourage you to cite our dataset if you have used them in your work :blush:. You can use the following BibTeX citation:

@inproceedings{xu2013uncovering,  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;title={Uncovering collusive spammers in Chinese review Websites},  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;author={Xu, Chang and Zhang, Jie and Chang, Kuiyu and Long, Chong},  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;booktitle={Proceedings of the 22nd ACM International Conference on Information and Knowledge Management},  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pages={979--988},  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year={2013}  
}
