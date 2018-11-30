---
title: "A Helpful Guide for Installing Apache Spark"
date: 2018-11-27
tags: [data science, big data, spark, anaconda, virtualbox, lubuntu]
header:
  image: "/images/sample-project/lootbox.jpg"
excerpt: "Data Science, Big Data, Spark, Anaconda, VirtualBox, Lubuntu"
---

# A Helpful Guide for Installing Apache Spark

*Hello! In this guide I hope to provide you a stress free way of installing Apache Spark onto your system along with Anaconda and Jupyter notebooks, 2 tools commonly used for the development and testing of Spark programs.*

*In order to follow along with this guide, you will need either A) a computer powerful enough to run a virtual machine with 4 GB of RAM or B) a computer with a distribution of Linux installed (Ubuntu 14 or later preferably)*

Well then, if you are ready, then lets get started!

We will be installing the following components:
+ VirtualBox (version 5.0 or later)
+ Lubuntu 14.04
+ Java 8
+ Anaconda
+ Apache Spark

*Note: If you have VirtualBox version of 5.0 or later, you do not need to install it again. Also, if you are on a machine that has a version of linux installed natively (such as a dual boot) you do not need to install VirtualBox or Lubuntu.*

## Installing VirtualBox and Lubuntu
You can install the latest version of VirtualBox on their [website](https://www.virtualbox.org/wiki/Downloads).

*You don't need the latest version of VirtualBox but I highly recommend version 5.0 or later for reasons you will see later.*

After you install VirtualBox, it is time to download a copy of Lubuntu, the distribution of Linux that we will be using. We will be downloading version 14.04.3 Trusty 64 bit which you can find either on [osboxes.org](https://www.osboxes.org/lubuntu/) or on my [dropbox](https://www.dropbox.com/s/74a269rnthtv6zo/Lubuntu_14.04.3-VB-64bit.7z?dl=0).

To set up the Lubuntu on VirtualBox, first extract the .vdi file from the Lubuntu download into someplace that you can find again. Next open up VirtualBox and click "New" to create a new virtual machine and fill in these settings:

Name: Whatever you want  
Type: Linux  
Version: Ubuntu (64-bit)  

Click Next. Type in a memory size of 4096 MB (4 GB).  

*Note: you can try giving less than this but you might run into memory issues in the long term*

Click Next. Select 'Use an existing virtual hard disk file' and select the lubuntu.vdi file that you downloaded.

Click Next. Now start your new Lubuntu vm. **The password is 'osboxes.org'.**
