---
layout: post
title:  "Data processing"
date:   2022-02-08 20:06:41 +0100
categories: processing
tag: processing
excerpt: The data processing group is responsible for reconstructing raw structural MRI images into 3D printable mesh files.
---

![brain image](/assets/img/DataProcessing.jpeg){:class="main-explain-area jumbotron"}

The data processing group is responsible for reconstructing raw structural MRI images into 3D printable mesh files. This focus group has tackled four major tasks:

Data Preparation: the data is prepared in BIDS file format and quality control of the dataset is performed. Artifact Correction: the surface of the brain is reconstructed from structural MRI using freesurfer and correction of artifacts is performed.

Brain Part Parcellation: brain parts are generated and merged of brain parts. The brain part parcellation is responsible for making a 3D base format of the MRI scan and highlighting each hemisphere, part of the brain and merging it into one single file.

Trimming the Brain: the parcellated brain is further processed and trimmed in open source 3D processing software (Meshlab).

Going forward, the team plans to create scripts, example data, 3D printable brain files, and guides in order to ensure that future students and other interested parties can easily 3D-print their own brains after acquiring a T1 fMRI scan of their brain. A preliminary guide for installing Freesurfer (software for processing T1 fMRI scans) for various operating systems and for completing a tutorial using the above modules will be available soon.

