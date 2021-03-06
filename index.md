---
layout: page
title: Cloudgene
---

Cloudgene is a framework to build Software As A Service (SaaS) platforms for data analysis pipelines. By connecting commandline programs, scripts or Hadoop applications to Cloudgene, a powerful web application can be created within minutes. Cloudgene supports the complete workflow including data transfer, program execution and data export.

 
<a class="btn btn-lg btn-success" href="http://docs.cloudgene.io" target="_blank" role="button"><i class="fa fa-download" aria-hidden="true"></i> Install</a>
<a class="btn btn-lg btn-primary" href="http://docs.cloudgene.io" target="_blank" role="button"><i class="fa fa-book" aria-hidden="true"></i> Documentation</a>
<a class="btn btn-lg btn-secondary" href="https://github.com/genepi/cloudgene"  target="_blank" role="button"><i class="fa fa-github" aria-hidden="true"></i> GitHub</a>

* * *

## Key Features

- **Build** your analysis pipeline in your favorite language or use Hadoop based technologies (MapReduce, Spark, Pig)
- **Integrate** your analysis pipeline into Cloudgene by writing a simple [configuration file](http://docs.cloudgene.io/developers/introduction/)
- **Get** a powerful web application with user management, data transfer, error handling and more
- **Deploy** your application with one click to any Hadoop cluster or to public Clouds like Amazon AWS
- **Provide** your application as SaaS to other scientists and handle thousands of jobs like a pro
- **Share** your application and enable everyone to clone your service to its own hardware or private cloud instance

* * *

## Who uses Cloudgene?

Cloudgene lives from its applications. Therefore, we've already developed two SaaS approaches (see below) and tested available MapReduce programs in the field of Genomics such as HadoopBam, Seal, Crossbow, Cloudburst or Myrna. If you’re interested to integrate your program please let <a href="/cloudgene-website/about">us</a> know.


### Michigan Imputation Server

*In cooperation with the University of Michigan, Gonçalo Abecasis & Christian Fuchsberger*

This server provides a free genotype imputation service. You can upload GWAS genotypes (VCF or 23andMe format) and receive phased and imputed genomes in return. Our server offers imputation from HapMap, 1000 Genomes (Phase 1 and 3), CAAPA and the updated Haplotype Reference Consortium (HRC version r1.1) panel. 
[https://imputationserver.sph.umich.edu](https://imputationserver.sph.umich.edu)


### mtDNA-Server

*In cooperation with the University of Innsbruck*

mtDNA-Server provides a free service for the analysis of human mitochondrial DNA data, currently focusing on reliable identification of heteroplasmy (>= 1%) and contamination. mtDNA-Server can be executed without any user login. We also provide post-processing guidelines that should be applied after each automated analysis. [http://mtdna-server.uibk.ac.at/](http://mtdna-server.uibk.ac.at/)
