# Drug Prices in the United States

## Abstract

The drug market in the United States has proven to be a very topical subject of study for the past few decades owing to a series of market trends and administration policy changes. A comprehensive study of the drug market in the United States will provide information useful for the formation of public policy, improve the efficacy of investment and provide valuable information to the consumer. The goal of this analysis is to provide a look at one component of the medical industry: drug prices. In this study, I explore the US drug prices by analysing what factors influence how drug prices change, measuring general trends in the marketplace, and building time series models to predict how individual drug prices will change.

## Methodology

### Data Wrangling

I am using the National Average Drug Acquisition Cost (NADAC) database available through data.medicaid.gov. To access this database, I am using the provided API to pull data directly from the dataset into the notebook. The API uses a limited number of SQL style functions through Socrata Query language (SoQL) which allows us to pull an arbitrary number of entries starting from the earliest entries in the database (2013).

The database is updated on a weekly basis. At this time, the entire database has 1.4 million entries. The database is large enough to make analysis of the whole thing infeasible without a distributed computation solution. This analysis will instead focus on the first two years of data in the database, although the code is written to be expandible to the user's requirements.

Each entry consists of an NDC code (which contains information regarding the labeler, the product, and the package of the drug), an NDC description (describing the drug name. dosage, and drug form), old price per unit, new price per unit, percent change and the start date for the change.

### Analysis

### Forecasting

## Results

## Planned Work
