# Isotope-based Hydrologic Partitioning Model (IsoHP)
## What is IsoPH?
This is a R code based version of the process used by UC-HAL hydrologists in order to better understand natural flows in the St.Mary/Milk River Basin (SMM) using unique isotopic signatures, enabling the tracking of sources and sinks within the system. The code is made to demonstate the process used in bit sized chunks, while also providing a tool to replicate these calculation for other hydrologic zones. Itstreamlines the process eliminating the need to perform manual calculation through spreadsheets, reducing the likelyhood of input errors.

## Presentation
The code can be downloaded as a single R project, which contain all the needed R scrips, and folders needed for the analysis. Each R script will read data from the Analysis Data dolder, the output the proccessed data into the, you guest it, the Processed Data folder. The output file will be in xlsx, allowing for easy readability, and further manual analyses for those wanting to expand upon this outlined process. The specific requirements for each file will be specified below for each R script/calulation process. This allows the user to the provided in any step of their analysis. This allows some flexibility, where due to lack of available data, a different method much be used for a specific test, which then allows the user to skip to the next step using the values resulting from their own calculations. At it's core, this code provides a mostly automated way to perform an isotope-based water balance, but provides the flexibility for users to section of the code they deem nessasary.

## Available R Scripts
Currently, not all the scripts needed are complete. Those that are available are as followed:


