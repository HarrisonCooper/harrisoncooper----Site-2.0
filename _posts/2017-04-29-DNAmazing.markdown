---
layout: post
title: DNAmazing - from disease to diagnosis in real time
permalink: hackmed17
image: /images/dnamazing.jpg
tags: [Python, Hackathon]
---

Devpost can be found [here](https://devpost.com/software/dnamazing)
Code can be found on GitHub [here](https://github.com/HarrisonCooper/DNAmazing)

# Awards
First Prize

# The Problem

Design, develop and present a solution to a problem facing the healthcare industry in 24 hours.

More than 2 million patients in the US develop antibiotic resistant infections every year. Although fast identification of resistant infections can improve outcomes, allowing the prescription of effective antibiotics as early as possible, bacterial culturing can take days. Doctors then need to chase up biomedical scientists for results, further increasing time until appropriate treatment can be administered.

# DNAmazing ARAlert

ARAlert is a tool for diagnosing Antibiotic Resistance (AR) rapidly using nanopore long read technology and the Comprehensive Antibiotic Resistance Database (CARD).

ONT reads are aligned to known AR genes in CARD using Burrows Wheeler Alignment (BWA) and the corresponding antibiotics are identified from the Antibiotic Resistance Ontology (ARO).

Discovering antibiotic resistance is a time sensitive matter. To fully utilise the speed of ONT sequencing, and to speed up time from sample to diagnosis, ARAlert includes automated text messaging and email reports using Nexmo API, to alert doctors as soon as results are available.

# The Future

This technology could be used for the fast diagnosis of a variety of infectious diseases through the detection of bacterial, parasitic and viral genomes. Oxford Nanopore RNA sequencing of human transcripts could also be used in the diagnosis of non-infectious diseases such as cancer or autoimmune disease, by using machine learning to identify diagnostic biomarkers.

# Build With
* Python
* Nexmo
* Oxford Nanopore Technologies
