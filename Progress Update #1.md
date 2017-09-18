
# Project Progress Report `#1`

**Theoretical Motivation:**
In keeping with the spirit of the Brainhack community, we decided to use the OBI project as an opportunity to further our own understanding of the reproducible tools we learnt during the course and to help others in the community to get started doing the same. We believe in *Learning-By-Doing* and plan to create a Jupyter Notebook based tutorial intended as a learning guide for beginners in the field to quickly step through the various early stages of doing MRI data analysis in a reproducible manner. Our guide will cover BIDS conversion, data quality control using MRIQC and data pre-processing using fMRIPREP pipelines.


**Research Design:** 
Since we are creating a beginner data analysis tutorial, we do not have a typical MRI research design to describe here. Our universal pipeline is research design-agnostic and works with any valid MRI dataset. The tutorial pipeline will be Jupyter Notebook based and will call upon existing Nipype based pipelines to perform various steps. We present further details of the actual flow of the pipeline in the code development algorithm below. 


**Statistical Analysis:** 
For this project, our focus is on interfacing the various steps of our tutorial pipeline together. Hence we will not be analyzing any dataset per se, but may use parts of different datasets (such as the MSC data) as test data for our tutorial. The usual caveats that apply to all MRI design and analysis (such as using a statistically efficient experiment design, having a well defined hypothesis at the outset and avoiding common statistical fallacies) apply here too. 


** Code Development:**
We have created an algorithmic block diagram below depicting various parts of our tutorial pipeline including what kind of input each Jupyter NB cell takes, what steps it performs, and the output it produces. We will use this algorithm as a template to develop 'code cells' in our tutorial notebook. Team members will work on a cell each in parallel, then we will interface parts that are next to each other to form the complete tutorial notebook.

