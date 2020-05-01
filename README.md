# Parkour Vault Research

Data for a parkour vaulting research project conducted as part of my undergraduate dissertation, [available to read online here](https://www.jmablog.com/_research/pkvs/pkvs.html).

## Data

The data folder contains all the data in a variety of formats, including the raw force curves for all participants in both .txt and .dat formats. The .dat files are the force profile files saved by [Bioware](https://www.kistler.com/en/product/type-2812a/) software directly, while the .txt files are the exported equivalent, containing some metadata at the top of the file. 

The cleaned and compiled data can also be found in Rdata, Excel, CSV and SPSS formats. Some formats also include the data in long or wide layouts, as preferred. Most variables in each format should be self explanatory, with the most important being the distinction between the force values being in Newtons (result\_n) or in multiples of participant bodyweight (result\_bw).

**Please be aware**: The compiled datasets (in the 'processed' folder and usually anything with 'pkvs' in the filename) for R/Excel/CSV/SPSS etc have been through a cleaning script, the one I used to perform the analyses used in the final paper. Mainly this affects the Precision Landing style figures, as these are **halved** to approximate the force through a single limb, in order to match the Running Landing style figures. The raw data (.txt and .dat files) contains the **original unhalved** figures for Precision Landings, if desired.

## Why are there so many file versions of the processed data?

Because I taught myself R to do this project, and went through a phase of experimenting with how it interacts with different file formats. Since I had them, I thought I might as well put them out there. They’re all the same underlying data; just pick whichever you prefer, or work from the raw files to start from scratch. 
