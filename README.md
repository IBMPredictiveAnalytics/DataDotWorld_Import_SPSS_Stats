# DataDotWorld_Import_SPSS_Stats

This extension allows you to import datasets from [Data.World](https://data.world/) into SPSS Statistics.

## Requirements

This extension requires the following
* IBM SPSS Statistics v25 or later
* IBM SPSS Statistics 'Essentials for R' plugin
* R v3.3

## Installation Instructions

This extension can be downloaded from the [Extension Hub](https://ibmpredictiveanalytics.github.io/)

## R packages used

This plugin will install the following R packages : 

* [Data.World](https://CRAN.R-project.org/package=data.world)
* [dwapi](https://CRAN.R-project.org/package=dwapi)
* [Properties](https://CRAN.R-project.org/package=properties)

## Other Requirements

This extension requires a Data.World Authentication Token. This token can be obtained from [here](https://data.world/settings/advanced)

## Steps

1. Download the extension from the Extension Hub

2. Click on File Menu -> Import Data -> Import from Data.World
    ![Image 1](/resources/SPSS_Image_1.png)
3. Enter the values for the following <br/>
    a. Data.World [authentication token](https://data.world/settings/advanced). This needs to be entered only the first time the extension is used.
    
    b. Data.World dataset URL : : This is the URL of the dataset of the dataset hosted on datadotworld. <br/>
    Example Dataset : <br/> 
    * https://data.world/jonloyens/an-intro-to-dataworld-dataset
    
    c. SQL Select statement to query the dataset. E.g. 
    ```
    SELECT * FROM datadotworldbballstats
    ```
    ![Image 2](/resources/SPSS_Image_2.png)
    
 4. The extension would then import the data into a new Data Editor Window.
    ![Image 3](/resources/SPSS_Image_3.png)
    
    
 ## Authors
 
* Deepak Rangarao
* Amod Upadhye

## Contact Information
For any issues while using this extension, please raise an issue on GitHub or send us an <a href="mailto:h6u9j3n4w2n7k6i7@ibm-analytics.slack.com">Email</a>
