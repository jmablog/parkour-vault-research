# Parkour Vault Research

Data and analysis scripts for parkour vaulting research conducted as part of a dissertation, available at: https://www.jmablog.com

## Data

The data folder contains all the data in a variety of formats, including the raw force curves for all participants in both .txt and .dat formats. The cleaned and compiled data can also be found in Rdata, Excel, CSV and SPSS formats. Most variables in each format should be self explanatory, with the most important being the distinction between the force values being in Newtons (result\_n) or in multiples of participant bodyweight (result\_bw).

**Please be aware**: The compiled datasets (in the 'processed' folder and usually anything with 'pkvs' in the filename) for R/Excel/CSV/SPSS etc have been through the cleaning script. Mainly this affects the Precision Landing style figures, as these are **halved** to approximate the force through a single limb, in order to match the Running Landing style figures. The raw data (.txt and .dat files) contains the **unhalved** figures for Precision Landings, if desired.
