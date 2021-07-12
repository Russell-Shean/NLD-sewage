# SARS-CoV-2 RNA in waste water in the Netherlands
The is a work-in-progress repository. In this repository are some ideas for how to map COVID-19 sewage sampling results for the Netherlands. Code was all written in R/Rmarkdown (not HTML)


# Concentration of SARS-CoV-2 RNA in waste water by sampling site in The Netherlands 40/2020-10/2020
<img src="https://github.com/Russell-Shean/NLD-COVID19-sewage/blob/main/Nld_sewageRNA.gif" width="400" height="auto" /> < img src="https://github.com/Russell-Shean/NLD-COVID19-sewage/blob/main/screenshot.jpg" width="400" height="auto" />

# Intro
- This is a tutorial that shows how to make a map of SARS-CoV-2 RNA sewage sampling results in the Netherlands. The data comes from this website:      
  https://data.rivm.nl/meta/srv/chi/catalog.search#/metadata/a2960b68-9d3f-4dc3-9485-600570cd52b9?tab=relations 

- For a more general explanation of SARS-CoV2 sewage sampling in the Netherlands (In English!😊):      
  https://www.rivm.nl/en/covid-19/sewage

# Workflow

1. Download data from this repository (or if you want a more recent version of the data, from the Dutch government website (☝️☝️ see link above ☝️☝️))
2. Download the shapefiles (Important: keep all the files together in same folder or directory!)
3. The main tutorial is presented in: NLD-COVID19-sewage-sampling.html 
   - The html file can be downloaded and opened in a web browser
   - Or viewed at the following link: https://tulipsfortaiwan.github.io/NLD-COVID19-sewage-sampling.html
   - The R markdown code used to make this html file is in: NLD COVID19 sewage sampling.Rmd

# Outputs

1. An animation of sampling sites's RNA concentrations over time: Nld_sewageRNA.gif
2. A zoomable map that shows data as color and RNA concentration as size: NLD_COVID19sewage_map.html       
   Also available at this link: https://tulipsfortaiwan.github.io/NLD_COVID19sewage_map.html 
 



# History
10/2020 Code was written         
07/2021 Code was organized, but not updated, or significantly changed (Data was not updated!) 

# Possible future directions
- Add map of sewer lines (perhaps focus on Amsterdam)
  - Add small admin units shape files + population data
  - Add buffer along sewer lines
  - Add gradient function for distance from sewage line + distance from sampling point
  - Calculate RNA/ population for each small admin area using distance gradient functions
  - Senstivity analysis and parameter selection for 2 gradient functions
  - Other factors? (Rainwater, sewer combined waste/rain or just waste?, etc)
