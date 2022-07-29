---
layout: default
title: How do I use the AWS CLI from my laptop?
---

The AWS Command Line Interface is a command line tool that enables you to perform all AWS actions that you can do from the AWS Web Console directly from your a command line.

OK: :unamused:

AWS CLI is a -very- elaborate tool. For help on using the tool please refer to the [User Guide](https://docs.aws.amazon.com/cli/latest/userguide/) and to the [Reference Guide](https://awscli.amazonaws.com/v2/documentation/api/latest/index.html)

There are two distinct ways in which to access the AWS command line interface (the 'aws' command)

## 1. Through the website

By far the easiest way to log in to the AWS console is through a so-called Cloud Shell. First log in to the AWS console on the web. Then, after making sure you are in the correct region (usually Frankfurt: *eu-central-1*), click on the CloudShell icon:

![Console](AWS-Management-Console.png)

## 2. Directly from your laptop or desktop computer

If you want to be able to use the AWS cli without using a browser (so that you can for instance run AWS commands as part of your own scripts), you will need to set up the cli environment on your own machine

1. Install the software.

    Follow the instructions on <https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html> in order to install the software on your machine. Linux, Windows and MacOS are supported.

2. Set up your access key.

    Follow the instructions on <https://docs.aws.amazon.com/cli/latest/userguide/getting-started-prereqs.html> in order to create an access key for use with the CLI.

    Then follow the instructions on <https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart>.html in order to configure your local setup to use the newly created key.
