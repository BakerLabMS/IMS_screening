# Streamlining Phenotype Classification and Molecular Annotations with Machine Learning: A Screening Method for Nontargeted Ion Mobility Spectrometry-Mass Spectrometry (IMS-MS) Data


## Usage
To run any of the r scripts provided, clone the repository and open the **IMS_Screening.Rproj** file in Rstudio.
Run the scripts within the project, so that they can find the relevant paths on your machine. 

## Folders
* **Raw_data** - This folder contains the raw data from the instrument and associated metadata that was loaded into R for the screening analysis. Files are split into additional folders based on the phenotype being studied. 
* **Code** - All code used to generate paper results are in this folder. Scripts are split by phenotype and the type of data that was used. 
* **Data_subsets** - Throughout the analysis, intermediate versions of the processed data were saved off so that the analysis could be picked up without having to run the code from the beginning. These intermediate forms are saved into this folder primarily as .Rdata files.
* **Analysis** - This folder contains any relevant figures or output that was generated during the analysis.


