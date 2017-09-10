# Project pitch

## Project name
**OBI-WAN** (**O**nline **B**rain **I**ntensive **W**ith **A**utomated **N**euro-pipelines)

## Contact information
Remya Nair (slack: \@rnair, github: nair-r)

## Description
The aim for this project is twofold: To put into practical use the various tools we learn on this course such as git, docker, jupyter, DataLad and nipype pipelines, as well as ensuring that the data formats, tools, and results are conducive to reproducible science. To this end, we will use BIDS format data and open-source pipelines, and create a workflow that will be shared in a Jupyter notebook.

Specifically, we aim to get an open access dataset (*INSERT DATASET*), convert the data into BIDS format, check the data quality using mriqc, and preprocess the data using fmriprep. We will use nipype to connect these steps and create a Jupyter notebook, to provide a well-documented and reproducible workflow that can be shared with, and easily adapted by the community. 

## Team
Team OBI-WAN (Remya Nair, Oana Tudusciuc, Samuel Guay, Samyukta Chillara, Somayeh Maleki, Armin Najarpour Foroushani, Kristina Wiebels, and Ilkka Kosunen)

## URL
https://github.com/nair-r/OBI-Neurotools-Project

---
#Initial pitch draft

# Over-arching aim:  Do reproducible science!
### Aim for the OBI course project is two-fold:
1. Put into practical use the various tools we learn on this course such as Git, docker, jupyter, DataLad and nipype pipelines.
2. Do above while also ensuring that the data formats/tools/results are conducive to reproducible science. To this end, we’ll use BIDs format data and share everything.

### Keeping in mind the scope of this course, we will use tools learnt to during the course to implement each step:
1. Create a Git repo and edit this document using various Git commands!
2. Get data from any open access dataset via datalad. (HCP. I’m flexible re. dataset.
   We can discuss as a group re. exact dataset and plans.)
3. Convert our dataset to BIDs format (yay reproducibility!)
4. Create a Dockerized (or Singularity) version of the mriqc pipeline and fmriprep pipeline.
   Both are nypipe based pipelines, so it’ll be a good way to get our feet wet with nypipe.
5. Customize the mriqc pipeline and run on some data to get automated quality control info. and generate visual reports.
6. Customize the fmriprep pipeline and run on some data to do some ‘automated’ pre-processing of functional MRI data.
ALTERNATELY/ OR in addition to above (depending on interest/time), we could implement a resting state functional connectivity analysis.
There are various nypipe tools available for that as well (e.g.: C-PAC).
7. Write code to document the steps taken above and the resulting images / results in a Jupyter NB with some pretty pictures to share with the everyone. :)

