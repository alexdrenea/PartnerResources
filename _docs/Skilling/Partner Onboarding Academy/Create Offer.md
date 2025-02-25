---
layout: page
title: Create an Offer
description: Are you ready to create an offer?
permalink: /skilling/partner-onboarding-academy/create-offer
updated: 2023-09-28
showbreadcrumb: true
tags: 
- academy content
- microsoft partner onboarding academy
- offer
---

## Microsoft Partner Onboarding Academy

After creating a Microsoft Partner Center account and getting your MPN ID, your next step in the journey is likely to create an offer.  This page will walk you through the important concepts necessary to create your first offer in Partner Center.

### Create an Offer in Partner Center

To create an offer, you must select the following.  This page will walk you through some of the different options.

- [Select an Listing Type](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type)
- [Select an Offer Type](https://learn.microsoft.com/en-us/partner-center/marketplace/publisher-guide-by-offer-type)
- [Select a Plan](https://learn.microsoft.com/en-us/partner-center/pricing-and-offers) (e.g. How much to charge)
- [Submit Offer for review](https://learn.microsoft.com/en-us/partner-center/marketplace/review-publish-offer)


### Offer Listing Type Options

An offer must have one of 4 different listing types:

- [Free Trial](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#free-trial): Make a software license available free for 30 to 120 days. (Customers will be charged for applicable Azure infrastructure usage)
- [Test Drive](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#test-drive)
- [Contact Me](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#contact-me): A simple listing of the offer which allows a potential customer to contact you.  Can be used to [generate customer leads](https://learn.microsoft.com/en-us/partner-center/marketplace/partner-center-portal/commercial-marketplace-get-customer-leads).
- [Get It Now](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#get-it-now): The only way to "Transact in Marketplace".  Must be one of the following licences: 
    - [Free](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#get-it-now-free): Not Marketplace Transactable
    - [Bring Your Own License (BYOL)](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#bring-your-own-license-byol): Not Marketplace Transactable
    - [Subscription](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#subscription): Charge a flat fee for monthly or annual subscriptions
    - [Usage Based Pricing](https://learn.microsoft.com/en-us/partner-center/marketplace/determine-your-listing-type#usage-based-pricing): Used to define custom or pre-defined billing metrics and rates (e.g. per vCPU, per seat, usage billing, etc.)
 
__PRO TIP__: Many partners start with "Contact Me" offer to get started.


### Offer Types

An technical portion of an offer will fall into one of the following Offer Types:

- [SaaS](https://learn.microsoft.com/en-us/partner-center/marketplace/plan-saas-offer)
- [Azure Container](https://learn.microsoft.com/en-us/partner-center/marketplace/marketplace-containers)
- [Virtual Machines](https://learn.microsoft.com/en-us/partner-center/marketplace/marketplace-virtual-machines)
- [Azure Applications](https://learn.microsoft.com/en-us/partner-center/marketplace/plan-azure-application-offer)
- [Dynamics 365](https://learn.microsoft.com/en-us/partner-center/marketplace/marketplace-dynamics-365)
- [Managed Service](https://learn.microsoft.com/en-us/partner-center/marketplace/plan-managed-service-offer)
- [Consulting Service](https://learn.microsoft.com/en-us/partner-center/marketplace/plan-consulting-service-offer)
- [And more!](https://learn.microsoft.com/en-us/partner-center/marketplace/publisher-guide-by-offer-type#list-of-offer-types)

Here are some additional details about some of the offer types:

### [Offer Type - SaaS](https://learn.microsoft.com/en-us/partner-center/marketplace/plan-saas-offer)

To integrate your SaaS with the MP, there are a few, great resources to get you started:

- [Mastering the Marketplace](https://microsoft.github.io/Mastering-the-Marketplace/saas/tech-topics/): Walkthrough of creating SaaS offer
- [SaaS Accelerator](https://microsoft.github.io/Mastering-the-Marketplace/saas-accelerator/): Provides a functional, technical implementation for SaaS solutions for getting started

### [Offer Type - Azure Container](https://learn.microsoft.com/en-us/partner-center/marketplace/marketplace-containers) 

[Azure Container Offers](https://learn.microsoft.com/en-us/partner-center/marketplace/azure-container-technical-assets-kubernetes) (a.k.a. Kubernetes Apps) offers are for solutions which can run inside an Azure Kubernetes Service (AKS) cluster.  Microsoft hosts your container images and helm chart, deploys into Customer AKS cluster and manages billing.  

- [Blog post](https://aka.ms/k8sapps)


### Private vs Public Plans

When creating the offer, you might want to offer a different pricing model for some customers that are not publically available.  This page will talk about the different options:

- [Private Plans](https://learn.microsoft.com/en-us/marketplace/private-plans) - A custom pricing plan of an Offer for a specific Tenant or Subscription

- [Private Offers](https://learn.microsoft.com/en-us/marketplace/private-offers-in-azure-marketplace) - Similar to Private Plans, but covers more scenarios (e.g. discounts, expiration dates, bundles, custom terms)
  - [Requires extra configuration](https://learn.microsoft.com/en-us/marketplace/private-offers-pre-check)
  - [Troubleshooting](https://learn.microsoft.com/en-us/marketplace/private-offer-troubleshoot)

__PRO TIP__: When possible, use a Private Plan.  If you create a private offer, it will need to be enrolled into any eligible programs separately (e.g. MACC eligibility).