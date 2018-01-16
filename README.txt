# moneybegetsmoremoney-anddebt
Group project website HKS

Dataset
1-1. World FDI Inflows in 2016:
World Map of  FDI, the data comes from UNCTAD statistics, and the economies with negative inflows or no available data have been taken out.
[Waiting for more input from Dawei]



1-2. World FDI Inflows by Country Group (2016):
1-2. (1) Go to UNCTADSTAT: http://unctadstat.unctad.org/wds/ReportFolders/reportFolders.aspx?sCS_ChosenLang=en
1-2. (2) Select the folder <Foreign direct investment>
1-2. (3) Select the subfolder underneath <Foreign direct investment flows and stocks>
1-2. (4) Click on the table icon shown up on the right <Foreign direct investment: Inward and outward flows and stock, annual, 1970-2016> 
1-2. (5) Download the data to excel format.
1-2. (6) Select the rows with the first field value equal to Low-income economies (World Bank), Lower-middle-income economies (World Bank), Upper-middle-income economies (World Bank), High-income OECD members (World Bank), High-income non OECD members (World Bank)
1-2. (7) Select the year 2016
1-2. (8) Modify the number formats to currency


2-1. FDI of Mexico (1982-2016):
2-1. (1) Go to UNCTADSTAT: http://unctadstat.unctad.org/wds/ReportFolders/reportFolders.aspx?sCS_ChosenLang=en
2-1. (2) Select the folder <Foreign direct investment>
2-1. (3) Select the subfolder underneath <Foreign direct investment flows and stocks>
2-1. (4) Click on the table icon shown up on the right <Foreign direct investment: Inward and outward flows and stock, annual, 1970-2016>
2-1. (5) Click on <Individual economies> tab to open a new table with country-level data
2-1. (6) Download the data to excel format.
2-1. (7) Select the rows with the first field value equal to Mexico.
2-1. (8) Select the year from 1982 to 2016
2-1. (9) Modify the unit to USD billions by dividing all FDI values by 1000
2-1. (10) Change the date format to 01-Jan-YEAR so that the D3 visualization runs (with the least amount of modification). This is done by using Excel's concatenate funcion.
2-1. (11) Make a transformation in Excel so that data is in 2 columns.
2-1. (12) Copy and paste the data in a blank tsv file.

2-2. GDP of Mexico (1982-2016):
2-2. (1) Go to IMF Data Mapper: http://www.imf.org/external/datamapper/datasets
2-2. (2) Click the button <World Economic Outlook>, it changes the page.
2-2. (3) Click the button <Gross Domestic Product (GDP)>
2-2. (4) Select the option <GDP, current prices: Billions of U.S. dollars>. There is another button with <GDP, current prices> but with different subline.
2-2. (5) Scroll down and click the button <All Data> with <EXCEL FILE> icon underneath.
2-2. (6) Download the data to excel format.
2-2. (7) Select the rows with the first field value equal to Mexico.
2-2. (8) Select the year from 1982 to 2016
2-2. (9) Change the date format to 01-Jan-YEAR so that the D3 visualization runs (with the least amount of modification). This is done by using Excel's concatenate funcion.
2-2. (11) Make a transformation in Excel so that data is in 2 columns.
2-2. (12) Copy and paste the data in a blank tsv file.


3-1. Mexico's FDI by Sector in 2012
3-1  (1) Go to stats.OECD.org.
3-1  (2) On the left hand column, select "Gobalization", then select "FDI  
         statistics according to Benchmark Definition 3rd Edition (BMD3)", and then select "FDI flows by industry".
3-1  (3) A data sheet will appear to the right; from the menu on top, choose 
         "Customize", then "selection", then "reporting country."
3-1  (4) A pop up window will appear. Uncheck all of the countries except 
         Mexico, then select "Industry" from top menu. Unselect all items except for those that are in caps. Finally, select "View Data" on the bottom right hand corner of pop up window. Export the file into a Excel sheet to retain personal file.
3-1  (5) Replace data from the JSON file provided on the d3 website with the 
         data found in excel file for the year 2012 only.
