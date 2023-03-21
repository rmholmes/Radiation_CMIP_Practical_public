# Radiation_CMIP_Practical

A series of python/jupyter-notebook based practical exercises using simple Earth energy balance models and pre-processed Global Climate Model simulation data from the Coupled Model Intercomparison Program Phase 6 (CMIP6, https://wcrp-cmip.org/cmip-phase-6-cmip6/) to understand past and future climate change.

Written by [Ryan Holmes](https://rmholmes.github.io/) for the University of Sydney, School of Geosciences course GEOS2115/GEOS2915: Oceans, Coasts and Climate Change in February/March 2023.

## Overview of each practical exercise

The practical exercises are organised into 3 weeks:
- `GEOS2115_2023_PracticalWeek2_EnergyBalanceModels.ipynb`: A practical using simple single-atmosphere layer energy balance models of the Earth to explore the greenhouse effect, the response of the surface temperature to volcanic forcing and the ice-albedo feedback. No external data required.
- `GEOS2115_2023_PracticalWeek3_HistoricalClimateACCESS.ipynb`: A practical that explores the mean climate (relationships between short and longwave radiation at the surface and TOA, albedo, surface temperature etc.) and changes over the historical period (1900-2014) using data from the ACCESS-CM2 Australian climate model.
- `GEOS2115_2023_PracticalWeek4_ProjectedClimateChangeinCMIP6.ipynb`: A practical that builds on the week 3 practical to explore future climate change as projected by ACCESS-CM2, as well as the MPI-ESM and CanESM5 climate models, using projections of future greenhouse gas emissions following Shared Socio-Economic Pathways (SSPs) 2-4.5 and 5-8.5.

More information on how the practicals work is contained within the jupyter notebooks themselves. These are intended to be run on an online platform such as https://edstem.org/.

## Required data

The week 2 practical does not require access to any data. The weeks 3 and 4 practicals require access to processed CMIP6 output data from ACCESS-CM2, MPI-ESM and CanESM5, as well as processed observational data from the ERA20C reanalysis. The data required was pre-processed from raw CMIP6 data on the National Computational Institutes Gadi Supercomputer (see https://opus.nci.org.au/display/CMIP/Data+Access+Information#DataAccessInformation-CMIP6PublishedData) using the CMIP6_Data_Processing_For_GESO2115.ipynb script. The pre-processed data (compressed `.tar.gz` file size about 700MB) is located in a separate github repository at https://github.com/rmholmes/Radiation_CMIP_Practical_data. On edstem.org, the jupyter notebooks currently assume that data is located in the folder `/course/data/`

Some image files used in the Jupyter notebooks are included in the `images/` sub-folder.

## Assessment

Assessment for the practical exercises was designed as a series of short answer questions embeded within the Jupyter notebooks themselves (in red text). Some of these questions require modifications to the code, creating new plots etc. Other questions require accessing some online resources. The students hand in the answers to all of the questions (total 100 marks) A one pdf at the end of week 4. The questions are collated in the `GEOS2115_2023_PracticalWeeks1-4_AssessmentQuestions.docx/.pdf`. Answers (including code, figures and marking guide) are in the `GEOS2115_2023_PracticalWeeks1-4_AssessmentQuestions_and_Answers.docx/.pdf` files.
