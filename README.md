# Air-Pollution-Tolerance
1. Air Pollution data for various states was extracted till year 2015 in india-air-quality-data2.zip folder. And for the year 2016 to 2020 is available in the air datasets folder. It contains the final merged file for all year of selective 7 states ( Delhi, Maharashtra, Gujarat, Tamil Nadu, West Bengal, Haryana and Kerala) in aircsv.csv in the same folder. The rest of the files in folder contain the csv to downloaded data and the same is merged in aircsv.ipynb.
2. Plant species that are native to various indian states is extracted in the plant_scraping.ipynb. CSV file for the same is species_details.csv.
3. APTI for various Plant species is gathered from the table given in Vol13_No1_Are_Lak_T1.jpg. The text from the image is read using the optical character recognition ( OCR ) api and cv2 library of python in apti_extraction.ipynb. APTI_Values.csv contain the csv contents for the same.
4. Tree and Forest Cover Extraction folder contains the tree cover and forest cover of different states across the alternate years from 2000 to 2019. It contains the various csv extracted for different years along with their corresponding python files. tree_cover.csv contains the tree cover details, forest_cover.csv contains forest cover details and green_cover.csv is the merge of two files. Tree cover + forest Cover as total attribute is present in Total_Green_Cover.csv. The area is given here in km^2.  
5. In AQI vs APTI.py one can see the correlation derived between the two and the corresponding scatterplot as well.
6. In AQI vs Green Cover.py one can see the correlation derived between the two and the corresponding scatterplot as well.
7. Linear Regression.py consists of the prediction of tree cover based upon the value of AQIs given.
Project Report Overleaf Link: https://www.overleaf.com/project/5e7c94608eb4030001ac2fda
