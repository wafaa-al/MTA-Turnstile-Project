# MTA Turnstiles EDA
Wafaa Alharbi

ـــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــــ
### Abstract:
October is the Breast Cancer Awareness Month, Unfortunately, breast cancer touches 1 in 8 women (12.4%) over the course of her life.
Glamified brand is proud to debut 2 new eyeshadow palettes that will support 3 organizations that do outstanding work for breast cancer education, research, awareness, and direct patient support.
From launch on 09/01/2021 at 3PM CST through the end of year 2020, $2 from each sale of the palettes (up to $200,000) will benefit The Breast Cancer Research Foundation, Living Beyond Breast Cancer, and The National Breast Cancer Foundation.

### Design:
The company is interested in harnessing the power of data analytics to optimize the effectiveness of street team work which is crucial to boost the sales and help women in their fight of Breast Cancer.The street team will be placed at the entrances to subway stations to market the new products.

### Data:
• This project based on the following datasets: 
1- MTA Turnstile dataset located at (web.mta.info/developers/turnstile.html) 
2- United states census located at (data.census.gov) 
3- MTA subway stations zip code dataset [located at] (https://raw.githubusercontent.com/reiffs/202107_Reiff_Metis_EDA_Project/d570eb9a8827ce14e7fbc3c632775c00fb5d332f/raw_data_sets/station_zips.csv)
• Data was used in this project for a period of 4 months from SEP to DEC 2020. • I used this close period to get a quick result in this period because these period after the corona pandemic, and the behaviour of people similar to the period of this year 2021 so we can produce approximate results.
Number of rows = about 2,5M rows
Number of columns = 15 columns

### Algorithms:
##### Data cleaning:
- Fixing the reverse counter problem.
- Dealing with outliers.
##### Data validation:
- Checking no nulls.
- Checking no duplicates.
- Fixing turnstiles issue such as (reverse counter, zero counter turnstile, overshooting counter turnstile).
- Grouping each turnstile
- Removing white space from columns.
- Remove DESC column.

##### Methodology of exploring the data:
Each subway station was mapped to its zipcode, the analysis was done on only the subway stations areas in Brooklyn, then filteriy,ng only to the busiest stations.
Different analysis was implemented to answer the following questions in most crowded stations in Brooklyn:
2.1) Are subway commuters in weekdays different than weekends? 
2.2) Is there specific day the subway gets busy?

### Tools:

#### The main technologies and libraries that used are: 


#### Technologies:
- Python
- SQL
- SQLite
- Jupyter Notebook
- Tabluea
#### Libraries:
- Pandas
- Matlibplot
- SQL
- Seaborn
- SQLAlchemy
- NumPy

## Communication:
<img src="https://github.com/Wafaa-Alharbi/MTA-Turnstile-Project/blob/main/images/Femele%20in%20nyc.PNG" alt="drawing" width="600"/>
<img src="https://github.com/Wafaa-Alharbi/MTA-Turnstile--/blob/main/images/MOST%20CROWDED%20STATIONS1.png" alt="drawing" width="600"/>
<img src="https://github.com/Wafaa-Alharbi/MTA-Turnstile-Project/blob/main/images/Top5Stations.png" alt="drawing" width="600"/>
<img src="https://github.com/Wafaa-Alharbi/MTA-Turnstile-Project/blob/main/images/NumberOfEntries-Day.png" alt="drawing" width="600"/>




