# Air-Pollution-Tolerance
1. Air Pollution data for various states is cleaned and processed in the AQI2.ipynb. AQI based on the air pollutants parameters is   calculated and mean for every five years is plotted against every 8 states that are selected.
  1) Data being retreived from indian-air-quaity dataset from a https://data.gov.in/dataset-group-name/air-quality site which is a              government site which is being stored after prepocessing in a zip file as indian air quality dataset.
  2)In data cleaning process  rows with missing values were removed and outliers were removed.
  3)Visualisations done
      AQI Level mean of Metropolitian Cities from year 2004-2014
      AQI Level mean of States in India from year 2004-2014
      AQI Level mean of 8 states from year 2000-2004,2005-2009,2010-2014
2. Plant species that are native to india is extracted in the plant_scraping.ipynb. BeautifulSoup is used to extract the data about the species available along with the states in which they are commonly found. CSV file for the same is species_details.csv.
3. APTI for various Plant species is gathered from the table given in Vol13_No1_Are_Lak_T1.jpg. The text from the image is read using the optical character recognition ( OCR ) api and cv2 library of python in apti_extraction.ipynb.

