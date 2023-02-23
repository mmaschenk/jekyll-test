---
title: Increasing quotas
layout: default
parent: FAQ
---
Your AWS account initially comes with default quotas that are rather limited. This is to prevent you from unknowingly spend more than you intend. However, for some situations these quotas are too limiting. A quota boundary you are likely to hit is the fact that there are no GPU machines available to launch in EC2.

Luckily, you can easily manage your quotas so that this restriction is removed.

An important note is that quotas are administered per region of AWS. That means that if you for instance change your quotas in the Frankfurt region (eu-central-1), they will not be changed also in other regions. You need to change the quotas in each region seperately.

Common resource limits you are likely to increase are:
-	Gpu machines
-	Elastic IP’s

In order to adapt quotas, do the following:
1. Type "quota" in the search box and select “Service Quotas” from the search results
2.	On the left hand side of the screen, select the menu item 'AWS services'
3.	In the 'Find services' box, type part of your service name (**ec2** in this example) 
4.	From the resulting service list, select the one that you need (**Amazon Elastic Compute Cloud (Amazon EC2)** in this example)


![Finding the relevant service](aws-quotas-1.png)

After selecting the service, you are presenting with all quota settings that apply to that service. This overview can be quite overwhelming (a whopping five pages for EC2). Finding the correct name is an art in itself and often not trivial. When you need help here, please contact us (<{{site.data.naming.teammail}}>).

For the example in this FAQ, we want to be able to use on-demand ec2 instances that provide GPU's, so we type the term **demand** in the 'Find quotas' box:

![Finding the relevant quota](aws-quotas-2.png)

Observe that quotas for **Running On-demand G and VT instances** are set at zero. Select this option and on the resulting details page find the 'Request quota increase' button.

![Quota details](aws-quotas-3.png)

Selecting the button presents you with a screen where you can specify the new quota value for the selected quota. In this case, you would enter the number of G-type instances of machines that you would like to have available in your account.

Handling of the quota change is (obviously) done by AWS, and usually works quite fast. Be aware though that there is not one set procedure for all types of quotas. Some of the options (for instance upping the quota on reserved instances) even will cost money to increase, so AWS will contact us (and we will contact you) before applying it. Again, when in doubt contact us (<{{site.data.naming.teammail}}>) and we will do our best to assist you with this!