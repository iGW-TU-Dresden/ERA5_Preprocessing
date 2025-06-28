# ERA5_Preprocessing
R Markdown document that guide the user in downloading and preprocessing daily and monthly averages from the ERA5 products: 2-metre temperature and total precipitation.

## About the ERA5 datasets

The **ERA5 Project** is the fifth generation ECMWF reanalysis for the global climate and weather available from 1940 onwards. ERA5 provides hourly estimates for a large number of atmospheric, ocean-wave and land-surface quantities. Data has been regridded to a regular lat-lon grid of 0.25 degrees for the reanalysis and 0.5 degrees for the uncertainty estimate (0.5 and 1 degree respectively for ocean waves). More information can be found at:
*https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=overview*

## About the scripts

The Rmd scripts are dynamic documents that combine narrative text with code chunks, guiding the user through the code execution. Both code routines filter the server requests and download the datasets specified for the user's time window. The scripts are organized into four main steps:

1. Setting paths and directories.
2. Defining variables and the time window of interest.
3. Entering the latitudes and longitudes of the rectangular area of interest.
4. Downloading the datasets of interest.
5. Preprocessing the NetCDF files for either a shapefile or a list of coordinates.

## About R and RStudio

**i. Download and Install**

Follow the instructions below to install R and run the R scripts.
1. R: Download and install R by following the link that corresponds to your operating system Windows, Mac, or Linux: *https://cran.r-project.org/*
2. RStudio: RStudio is an application that assists you in writing R code. You can download it from: *https://posit.co/downloads/*
Once you have both R and RStudio installed on your computer, you can begin using R by opening the RStudio program. For more information, visit: *https://rstudio-education.github.io/hopr/starting.html*

**ii. To open an R Markdown (Rmd) file in RStudio**

1. Open RStudio: Launch RStudio on your computer.
2. Open Rmd File: Once you're in RStudio, you can open an Rmd file in one of the following ways:
- File > Open File.
- Drag the Rmd file from your file explorer and drop it onto the RStudio window.
3. Run: Once the Rmd file is open, you can run the individual chunks of code by placing your cursor within the chunk and clicking the "Run" button in the toolbar or using the keyboard shortcut *Ctrl+Shift+Enter*.

### Contributors

M.Sc. Olawale Joshua Abidakun (TU Dresden)

M.Sc. Maria Alejandra Vela Castillo (TU Dresden)

### Questions

Please contact: Prof. Dr. rer. nat. Andreas Hartmann | andreas.hartmann@tu-dresden.de
