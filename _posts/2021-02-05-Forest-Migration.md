---
layout: post
title: How to Migrate a Domain to New Forest
subtitle: This is just a small guide to perform a smooth Migration
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
tags: [Active Directory, Migration, ADDS]
comments: false
---

I have been involved in a Forest to Forest Migration recently and I wanted to share with you a very short guideline that will help you if you have ended up performing a Full Domain Migration to a New Forest. 

## Scenario
* There is a Root domain _contoso.com_ which has a child domain called _corp.contoso.com_
* The child domain needs to be separated from its parent. 
* A new Forest is created for that purpose and it will be called _oldboyschool.com_.
* For this scenario to work, I will be using **Active Directory Migration Tool** aka [ADMT v3.2](https://www.microsoft.com/en-us/download/details.aspx?id=56570),and **Password Export Server** aka [PES v3.1](https://www.microsoft.com/en-us/download/details.aspx?id=1838).

####This will be continued on a later stage. 
