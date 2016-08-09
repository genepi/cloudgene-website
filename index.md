---
layout: page
title: Cloudgene
---


Cloudgene is a platform designed for Hadoop MapReduce. It provides a graphical user interface for the complete MapReduce workflow including data transfer, workflow execution and data export. It provides feedback at any point.
The overall goal of Cloudgene is to build a standardized workflow execution environment for currently available and future MapReduce programs, which can all be integrated into Cloudgene.

<a class="btn btn-success" href="/cloudgene-website/getting-started">Getting started</a>

* * *

## Who uses Cloudgene?

Cloudgene lives from its applications. Therefore, we already integrated available MapReduce programs in the field of genomics such as HadoopBam, Seal, Crossbow, Cloudburst or Myrna into Cloudgene. If you’re interested to integrate your program please let us know.


### Michigan Imputation Server

*In cooperation with the University of Michigan, Gonçalo Abecasis & Christian Fuchsberger*

This server provides a free genotype imputation service. You can upload GWAS genotypes and receive imputed genomes in return. The underlying imputation engine is base on minimac, which implements a low memory, computationally efficient algorithm for genotype imputation that can handle very large reference panels with thousands of haplotypes. The current version of this server uses the 1000 Genomes Project phase III release as a reference for imputation.

[https://imputationserver.sph.umich.edu](https://imputationserver.sph.umich.edu)


### mtDNA-Server

*University of Innsbruck*

This server provides a free mtDNA alignment and heteroplasmy detection service. You can upload either single/paired FASTQ or BAM files and receive BAM files (in case of FASTQ input), detected heteroplasmies, interactive reports and haplogroups in return. The current version of this service uses a parallelized version of BWA MEM for alignment and includes different filters (e.g. BAQ, quality filters, statistics methods) to determine heteroplasmies reliable. All steps are executed in parallel using Cloudgene and the Hadoop framework.
mtDNA-Server

[http://mtdna-server.uibk.ac.at/](http://mtdna-server.uibk.ac.at/)
