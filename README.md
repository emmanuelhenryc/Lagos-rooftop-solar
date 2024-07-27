# LAGOS ROOFTOP SOLAR POTENTIAL FOR POWER GENERATION AND C02 REDUCTION WITH EDA
![image](https://github.com/user-attachments/assets/15f2fedc-1797-489a-aa2f-a6ad8fd7af7a)
![image](https://github.com/user-attachments/assets/3b059da0-8ad6-4d8e-b04a-a194453e1429)




## 📑 Description

 Estimation and Exploratory Data Analysis (EDA) of Lagos rooftop solar potential using a sample data of buildings in Lagos. By identifying the solar potential of building rooftops in Lagos, the aim is to understand the distribution of rooftops installable area and the likelihood of future “solar-prosumer” buildings in Lagos which helps in significantly reducing C02 equivalent emissions.

Also, to understand factors affecting the energy potential per year(kWhr). Factors such as – rooftop surface area (square metres), rooftop potential installable area (square metres), rooftop peak installable solar panel capacity (kW), rooftop estimated tilt (degrees), estimated building height (metres), estimated solar capacity factor (percentage).

![image](https://github.com/emmanuelhenryc/Lagos-Rooftop-Solar-Potential/assets/102620987/1aab214d-e2b7-4e86-982c-cf777ed36246)



## ⌛ Dataset
 To download the dataset for Lagos rooftop solar potential [click here](https://energydata.info/dataset/lagos-rooftop-solar-potential-mapping "Just a click!")



## 🛠️ Tools
- Python (Jupyter notebook) – data cleaning and EDA (which include plots.)
- VScode - Files management
- Git - Project management 


## 🔲 Data Cleaning
-	Data loading and inspection
-   Checking for duplicated rows
-	Handling of missing values 
-	Dropping of columns
-   Creating a new column



## 📈📉 EDA

To understand:
-	The summary statistics of each column
-	The correlation between features 
-	The distribution of each feature



## 💡 Findings: 
-	Rooftop surface area, rooftop potential installable area, and rooftop peak installable solar panel   capacity are perfectly positively correlated to energy potential per year.

-	Rooftop estimated tilt and estimated building height are weak and inversely correlated to estimated solar capacity factor.

-	The percentages of building type total surface area are: 
    ***single-family residential, 49.2%; peri-urban settlement, 20.2%; commercial, 8.8%; industrial, 11.2%; public, 6.6%; multi-family residential, 3.9%.***

-   The percentages of building type total volume are: 
    ***single-family residential, 49.9%; peri-urban settlement, 14.0%; commercial, 9.4%; industrial, 14.8%; public, 7.9%; multi-family residential, 4.0%.***


    

-   _Low-Carbon Power Project_, a resource for information on global electricity consumption and carbon       emissions, cities that:
        
    > Nigeria's electricity grid has a carbon intensity of 394.41 grams of C02 equivalent (gCO2e) per       kilowatt-hour.


    | Building Type | Building Count | Sum of Surface Area (sq km)|Sum of Solar Energy Potential per Yea(GWh)| 
    | :-------| :-------| ---------|------- |
    | Single family residential   | 121, 119 | 26.90 | 4, 090 |
    | Peri-urban settlement       | 48, 772 | 11.06 |1, 799|
    | Industrial        | 9, 827 | 6.13 |1, 109|
    | Commercial        | 15, 173 | 4.82 |757|
    | Public        | 9, 405 | 3.62 |587|
    | Multi-family residential   | 5, 614     | 2.15 |338|
    | **Total** | **209, 910** | **54.67**| **8, 680** |

    If 100% of rooftop potential is harnessed, that is **8, 680 GWh**, C02 equivalent (gC02e) emissions is reduced by **3.42 Megatonne (Mt)**.



## 🌟 Recommendations: 
1.	Policy on decarbonization in Lagos should be more focused on single-family residential, industrial and commercial buildings. single-family residential because of the building count, industrial and commercial because of the buiding count and also the use of large amount of power.

2.  Buildings with high solar potential but low funding for solar panels should be open for deals with electricity investors who are wiling to strike a deal to harness the solar potential of roofrops. 

3.	Roofs should be as wide(less tilt) as possible to accommodate more solar panel.

4.	Solar panels with greater capacity should be used for houses with little surface area.

5.	If renovation of roofs be done, roof should be about angle 0 to the horizontal. Or solar panels should be mounted at 0 degree to the horizontal.

6.	Factors affecting solar capacity factor, such as – building height, panel tilt, shadings near buildings… should be considered when building.



    
