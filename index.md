---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Welcome
---
## What is Cloud4Research?
Cloud4Research is a TU Delft IT service to facilitate the use of public cloud for research.

Initially Amazon AWS is supported. This will be extended in the future, according to demand and available resources.

{% capture termsofuse %}{% link 10-policy/termsofuse.md %}{%endcapture%}
{% capture finance %}{% link 10-policy/finance.md %}{%endcapture%}
## How does it work?
You can apply for an AWS account by filling in this form **todo** and agreeing to our [terms of use]({{ termsofuse | relative_url }})

A member of the Cloud4Research team will then schedule a meeting to discuss your infrastructure and support needs and your [financial requirements]({{ finance | relative_url }}).

## What do you get?
An AWS account with management rights. A limited initial budget to help get you started. The option to supply a project code for further expenses. Monthly and threshold budget notification emails. No more personal credit cards!

Initially, that's it. The Cloud4Research team is busy studying and hoping to expand, so that they can provide more advice and support in the future.

## What is a public cloud?
A public cloud provider offers managed, on-demand computing services and infrastructure through the public internet. Well known examples include Amazon AWS, Microsoft Azure and Google GCP. They allow you to 'build' anything from one simple computer to a whole data centre, without having to buy, power, connect, cool, install and maintain the hard infrastructure.

## How do I get started?
For AWS, [this is a good place to start](https://aws.amazon.com/?aws-products-featured).

## I have a problem with my AWS account. Where do I go for help?
Try the [Frequently Asked Questions]({{site.baseurl}}/faq).
