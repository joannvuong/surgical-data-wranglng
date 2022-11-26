# NSQIP Surgical Data Wrangling Project
## Overview
The American College of Surgeons National Surgical Quality Improvement Program (ACS NSQIP) is taking an approach for surgical procedures by working with hospitals to develop best practices around certain procedures with the objectives of preventing surgical complications, saving lives, and reducing healthcare costs. The main goal of this analysis is to determine whether hospital medicare claim type files can be used to participate in the ACS NSQIP program. We've selected 6 different NSQIP measures, and will use them to help determine whether or not these files can be used to participate in the NSQIP program: <br >

1) Deep vein thrombosis or pulmonary embolism after vascular or general surgery <br>
2) Colon Surgery Outcomes<br>
3) Death 30 days after surgery<br>
4) Sepsis after surgical site infection after surgery<br>
5) Pneumonia<br>
6) Urinary tract infection<br>

 
### Data
We will be evaluating and collecting most of our data through the Centers for Medicare & Medicaid Services (CMS) website and the SyntheticMass website.  Data provided by CMS and SyntheticMass provides a robust set of metadata for us to analyze, we hope to use at least one of these datasets for this project. The data provided by CMS are based off of claims which are all archived in a CSV file for us to evaluate. The data that is pulled from SyntheticMass contains one million synthetic patient medical records for us to examine, a few of our variables of interest are: claim ID, claim dates, admission dates, discharge dates, death dates, and ICD-9 codes.

###
