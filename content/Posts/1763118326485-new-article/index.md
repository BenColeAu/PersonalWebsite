---
title: "Welcome"
date: 2025-11-14
draft: false
description: "Welcome"
tags: ["Welcome", "tag"]
---
# Welcome

Over the course of this week I will begin publishing my application packages starting with the most commmon such as Chrome, Adobe, Autodesk, 7zip & the like. I feel a common repo of Intune application packages is needed when the windows Store deployment falls short of its offerings. Of course there are tools that are on offer such as PMPC or Robopack a new offering in the market for application management. 

Even with the existance of these tools there are still many envrionments that are being managed manually without these automated tools and there will always be a need for the LOB applications to be packaged manually due to installs not being publically available.

Many in the Australian local government might find a lot of these app packages useful as several agencies & organisations recycle the same pieces of software such as Content Manger by OpenText. I feel its needed to save us all a couple of hours building and testing deployments.

My goal overtime is to build up this repo and allow others to also contribute, I'll aim to include useful items like SHA & Publish rules for application control which should aid in managing WDAC the replacement for applocker.

WDAC (Windows Defender Application Control) is included with the E5 license which many larger organisations leverage but it falls short on the mark and in my opinion is quite difficult to admister although is quite easy to achieve Level 3 compliance with the Essential 8 framework.

In my next article I will publish the link to the repo which will be located on my github providing a simple readme for each package with the required install, Uninstall & detection methods for the application. In the future I hopefully can find sometime to circle back to these and also put in the WDAC rules I will aim to use the Publisher rule where possible however many applications still fall short on the mark for signing there apps. This also means that fewer changes to WDAC should be required as newer versions should be signed by the same publisher certificate.

If you are interested in contributing to this repo please do so via github and I will review pull requests as quickly as possible. Please ensure all packages are made generic and with things like organisational details and license keys excluded and replaced with placeholders.

{{< github repo="bencoleau/intune" showThumbnail=true >}}

Best of luck. 
Ben

