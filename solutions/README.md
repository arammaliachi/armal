# Dentsu Inc. Data Labs

The purpose of this solution is to ingest, process and analyze data of ongoing advertising campaigns running on digital, tv, radio, cinema and other media types for [Mastercard LATAM](https://latinamerica.mastercard.com/es-region-lac.html) by [Dentsu Inc.](https://www.dentsuaegisnetwork.com/)

**Data sources**:  

data  
**|--** [Lumina Mastercard Site](https://www.mediaocean.com/ca/products/lumina).  
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Media plan  
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Flight  
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Subflight  
**|--** [Teads](https://www.teads.com/).   
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Daily reports for running campaigns   
**|--** [Facebook Ads](https://www.facebook.com/business/tools/ads-manager).   
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Daily reports of Facebook Ad Accounts  
**|--** [Google Ads](https://ads.google.com/home/).  
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Daily reports of performance statistics of for MCCs.  
**|--** [Twitter Ads](https://ads.twitter.com/).  
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Daily performance metrics for Twitter ad accounts at a line item level.  
**|--** [Mediamath T1](https://t1.mediamath.com/).  
**|&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;|--** Daily report on performance metrics for agency HISP_LATAM_AMNET.  


![AWS solution](/solutions/architecture/aws-solution.png)

Our solution ingests, processes and analyzes all these data sources to extract meaningful insights about **campaign performance**, **account management** and **budget status** in an automated fashion.

We deliver automated reports and dashboard visualizations to [Amazon Quicksight](https://aws.amazon.com/quicksight/) and [DOMO](https://www.domo.com/).
