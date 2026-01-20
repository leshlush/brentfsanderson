+++
date = '2026-01-19T18:29:54-06:00'
draft = false
title = 'Advice for Edtech Startups'
tags = ['education', 'technology']
featured_image = 'images/magnetic.png' 
summary = 'Scattered thoughts for founders after a decade in the trenches'
+++

Below are some scattered thoughts offered to all education technology startup looking to sell a new product into K-12 schools. They come after a decade in the trenches:

* Many districts' content filtering software has a blanket ban on all .io domains. Don't give your web app a .io address unless you want to spend a ton of time helping confused teachers apply for a whitelisting exception.    
* Districts will care about your student data privacy policies. You will be asked if you are compliant with FERPA and COPPA. Do you know what those are? Are you compliant?    
* Many districts have a policy that students cannot use any application that involves signing in with a username and password. How will you grant those students access?
* Does your web application make use of the browser's local storage like IndexedDB or the Cache API? Many managed Chromebook policies used by schools either prevent local storage altogether or clear the cache at regular intervals. If that breaks your app, you need to find a solution.  
* Many schools' content filtering blocks common CDN platforms. If you use a CDN to serve static assets as part of your application, make sure you to include the CDN's URL as part of your list of domains that need to be white-listed by IT staff. It's very possible you're serving assets from multiple subdomains, so be sure to include each one.    
* If you're trying to launch a product and most schools or districts don't have a line-item in their budget to buy that product, you should strongly re-think trying to launch that product.

