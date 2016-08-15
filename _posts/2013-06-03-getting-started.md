---
layout: page
title:  Getting started
date:   2013-06-03 21:12:57
category: doc
order: 0
---

This page helps you to install, configure and running Cloudgene on your own Hadoop cluster.


## Requirements

Cloudgene requires the following software packages in order to work properly:

*   Apache Hadoop (MRv1 or YARN; We highly recommend <a href="https://www.cloudera.com/products/cloudera-manager.html">Cloudera Manager</a> for seting this up)
*   Java 1.7 (For HTSJDK, Java 8 is required for Hadoop) 
*   jsvc
*   Optional: R (packages: RMarkdown, knitr, ggplot2)


## Download and Installation

Download the latest version from our <a href="/cloudgene-website/about">download</a> site.

    
Extract the zip file and change the permissions of the executables:

    unzip cloudgene.latest.zip
    chmod +x cloudgene


Now you are ready to start and configure Cloudgene.


## Running Cloudgene

Start Cloudgene by entering the following command:

    ./cloudgene -a start -u <hadoop-user> -p <port> -j <java-dir>


Check if Cloudgene is running properly:

    ./cloudgene -a status


Cloudgene can be stopped with the following command:

    ./cloudgene -a stop




## Configuration

1.  Open your browser and navigate to `http://localhost:8082`.

2.  Login as admin with the default admin password 'admin1978'

3.  Change your password immediately (click on profile or go to `http://localhost:8082/start.html#!pages/profile`)

4.  Go to Admin-Panel and set the path to your Hadoop Installation. If you installed Hadoop using the Cloudera Manager the path of your Hadoop Binary is `/usr/bin/hadoop`. You can check this by enter `which hadoop` on the command line to get the full path.

    ![enter image description here][1]

5.  Next, configure the mail server used by Cloudgene to send notifications and activation links:

    ![enter image description here][2]



## Verifying your Installation

Cloudgene is delivered with a preconfigured application. This can be used to test that Cloudgene detects your Hadoop cluster and works properly. To run this test, please follow these steps:

1.  Click on Run and the following formular appears:

    ![enter image description here][3]

2.  Click on "Validate my Configuration" in order to ensure that Cloudgene is able to communicate with your Hadoop Cluster.

3.  If the job fails, please read the error message and adapt your configuration until the job runs successfully.

4.  Now you are ready to use Cloudgene!


 [1]: {{ site.baseurl }}/images/hadoop.png
 [2]: {{ site.baseurl }}/images/smtp.png
 [3]: {{ site.baseurl }}/images/check.png
