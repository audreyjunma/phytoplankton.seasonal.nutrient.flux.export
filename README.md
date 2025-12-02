# Analyzing Effects of Light and Nutrient Availability, Seasonal Variations, and Sea Ice Concentration on Ocean Phytoplankton in a Changing Climate: Modeling Bloom Dynamics, Carbon Flux, and Sea-Ice Interactions

This Jupyter Notebook contains the code necessary to recreate all of my figures and work for my study on how variables such as light availability, nutrient availability, This project is currently mentored by Dr. Andrew Thompson, the director of Caltech's Linde and Maxine Center for Global Environmental Science, and Sarah Zhang, a current Caltech graduate student in the Linde and Maxine Center for Global Environmental Science. Though I made final presentation to conclude this project for the summer before I returned to school, this is an ongoing project as is my internship at Caltech, and thus there may be updates.

**NOTE:** This project was originally completed on Google Colab and was adapted into a Jupyter Notebook. Please see README for instructions to create a proper working directory. If you need any other resources (i.e. would like to recreate the project within Google Colab, additional data, etc.) feel free to email me at audreyjunma@gmail.com.

## Background Information
The Southern Ocean's sea ice concentration reached a record high in 2014 and has decreasing ever since, decreasing noticeably starting in 2016, until it reached a record low in February of 2016. The Southern Ocean accounts for around 40% of the world's oceans' global uptake of anthropogenic carbon dioxide, and phytoplankton activity (photosynthetic processes) in the Southern Ocean account for 50-75% of that 40% contribution (i.e. 20-30% of the world's oceans' carbon uptake). In the Southern Ocean, photosynthetic activity of phytoplankton depends on two main factors: light availability and nutrient availability, specifically the availability of iron. Since the coverage of sea-ice can inhibit the passage of light for the phytoplankton to receive, this project aims to analyze how seasonal variations and sea-ice interactions that influence light availability influence phytoplankton populations living underneath sea ice. 

## Installation Requirements
1. Access to downloadable files the MEOP Database,  **LINK TO MEOP DATABASE:** https://www.meop.net/database/meop-databases/meop-ctd-database.html
2. Access to downloadable files from the NSIDC Sea Ice Concentration Database, **LINK TO NSIDC SEA ICE CONCENTRATION DATABASE:** https://nsidc.org/data/nsidc-0051/versions/2
3. Jupyter Notebook
4. Relevant Python Libraries (see notebook)

## Usage Requirements
The notebook contains different directories that are referenced — of course, you can change them if you would like to, but if you would like to have directories that work with the notebook, create the following empty directories within your working directory.
  1. One directory titled "Code" (don't include quotes), in which you should place the notebook included in this repository
       a. Within this directory you should also create another empty directory called "Processed Data" where the notebook can save processed data to access later
  3. One directory titled "Data" and the following directories within this directory
       a. One directory titled "MEOP" in which you should place all the files you downloaded from the MEOP Database
       b. One directory titled "SIC" in which you should place all the MONTHLY sea ice concentration files you download from the NSIDC Database
           1. Within this directory, you should also place another directory called "Daily SIC" in which you should place all the DAILY sea ice concentration files you download from the NSIDC Database
               a) Within this directory, you should also create another empty directory called "Processed" where the notebook can save processed data to access later

## Usage Examples
This notebook was initially created in an internship at Caltech's Linde and Maxine Center for Global Environmental Science. 

See images of figures from this notebook here: https://drive.google.com/drive/folders/1amnPzMdTfGwJJ76Sbm3Ov9KRWdxvALKo?usp=sharing

See the major progress point presentation here: https://www.canva.com/design/DAG6QTY85S8/68w1TFFip0YZWgzkiJEIug/edit?utm_content=DAG6QTY85S8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## Authors + Acknowledgements
All code is original code written by Audrey Ma. Special thank you and acknowledgement to Dr. Andrew Thompson, director of Caltech's Linde and Maxine Center for Global Environmental Science, and Sarah Zhang, a current Caltech graduate student in the Linde and Maxine Center for Global Environmental Science, for mentoring this project. 

I would also like to acknowledge these papers that were helpful in this project: 

*Boyd et al. 2024* **"The role of biota in the Southern Ocean carbon cycle"**
Link: https://www.nature.com/articles/s43017-024-00531-3#Abs1

*Deppeler and Davidson 2017* **"Southern Ocean Phytoplankton in a Changing Climate"**
Link: https://www.frontiersin.org/journals/marine-science/articles/10.3389/fmars.2017.00040/full

*Purich and Doddridge 2023* **"Record low Antarctic sea ice coverage indicates a new sea ice state"**
Link: https://www.nature.com/articles/s43247-023-00961-9

*Meiners et al. 2012* **"Introduction: SIPEX-2: A study of sea-ice physical, biogeochemical and ecosystem processes off East Antarctica during spring 2012"**
Link: https://www.sciencedirect.com/science/article/abs/pii/S0967064516301710?via%3Dihub
