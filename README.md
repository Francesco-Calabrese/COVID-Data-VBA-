# COVID-Data
Displays COVID data for selected country during a given time range


**How it Works**
1. Select the country in the first drop-down box. Once you start typing it will auto-fill the country. Once the country is selected, tab out of the box to continue.
2. If the US is selected as the country, two additional drop-down boxes will appear. Enter a state in the box below the country, and a county for the box below the state. 
3. Enter the start and end dates in blocks D6 and E6. The format must match MM-DD-YYYY.
4. Click the Get Data button to retrieve the data. Note, the data retrieved will be saved to the Data Sheet Worksheet and will be overwritten for each day. 
      
      Data is retrieved from CSSEGISandData's GitHub (JHU CSSE COVID-19 Data, and the url: https://github.com/CSSEGISandData/COVID-19)
      
5. As the data is being retrieved, the percent complete will display on the bottom left in the application status bar.
6. Once the data is retrieved, it will display on the two graphs. Another button called the Percent Change Button will display above the date input cell if you want to view the percent changed, which will display on the two graphs on the bottom. 
7. Click the Clear Data Button to clear the data. 


**Images**

![image](https://user-images.githubusercontent.com/96243400/146383773-3e177dca-641d-4299-9d7e-3077ccd640f7.png)


![image](https://user-images.githubusercontent.com/96243400/146385874-777c7b58-97cf-4116-bc37-87a8e36b73af.png)


![image](https://user-images.githubusercontent.com/96243400/146386665-8ea5ad51-2420-4303-a900-b30556711fb5.png)



**Updates**
1. If the US is selected, the user is no longer requred to selected a state or county. If a state is selected, the user is no longer required to select a county. It will add up the sum of the country or selected state.
2. Added a Vaccine Doses Given Button, which gets the vaccine data for the selected country or state (US only). This button is displayed once the COVID data is retrieved. 

3. Added daily changes button to see the difference in cases/deaths between two days.
4. Added the total change in cases and deaths from the time range given.

The vaccine doses data is retrieved from BloombergGraphics GitHub account (https://github.com/BloombergGraphics/covid-vaccine-tracker-data). 

![image](https://user-images.githubusercontent.com/96243400/146611190-017d4b6a-e74b-4a73-811c-63d52179e497.png)

![image](https://user-images.githubusercontent.com/96243400/146814573-e43b1e9e-643d-4c45-bdc6-108b081a72b8.png)

