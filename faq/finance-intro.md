---
layout: default
title: How are costs calculated exactly?
parent: FAQ
---

## How are costs calculated exactly?

This page is meant to provide you with some background on how we calculate costs for {{site.data.naming.servicename}} accounts.
TU Delft buys its cloud resources through the EU instigated [OCRE](https://www.ocre-project.eu/) project. This project aims to provide (public) cloud facilities for researchers and universities in all EU member states. 

Each member state is responsible for setting up its own national method of providing institutions with cloud resources. In the Netherlands, the way this is set up is through [Surf](https://www.surf.nl/). TU Delft has signed a contract with Surf to provide us with an AWS account. This means we get a monthly bill from Surf, based on our (that is, TU Delft's) usage for that month.

A complicating factor in payment of this bill is that we -obviously- receive this bill in euro's, but all calculations that are made at Amazon are in dollars. This means the amount that we pay for cloud services depends on the exchange rate for dollars in any given month. Another complicating factor is that we receive the bill for a given month quite a long time after that month has passed. Fortunately we receive information on our own spending much earlier through AWS, so we are able to calculate TU Delft's (and also our researcher's) costs much sooner.

The process we employ is as follows: first we wait until AWS has marked the preceding month as "final" (this usually happens in the first week of the new month). Then we add up all expenses that we retrieve from AWS (in dollars!) and convert this to euros using an average exchange rate that we retrieve from [https://currencyapi.com/](https://currencyapi.com/). We then subtract the base financing from the bill for each account, create the PDF version of the bills and send these out to the account owners (researchers) and supporters (budget-holders). Finally we create an overview of all amounts due and deliver this to our finance department who will do the actual accounting on the researcher's budget-code.
