# Korcan-Baykal-DSA210-Term-Project
## Project Overview
For a long time, I have been seeing news about the increase in air pollution and its effects both in our country and around the world. However, I realized that there are many factories in the city where I live and around us. Therefore, I started to wonder how the changing number of factories over the years affects the amount of air quality and the harmful gases in the air. Also I wondered whether the air pollution where we live is highest in the hot months or in the cold months.

The plan is as follows: I will collect the annual number of factories from the provincial industrial status reports of the Ministry of Industry and Technology. At the same time I will collect 2 different harmful particle diameter(PM10, PM2.5) datas and 6 different chemical compound(SO2, CO, NO2, NOX, NO, O3) gases datas related with air pollution from the databank of the national air monitoring network of the Ministry of Environment, Urbanization and Climate Change. Finally, I will compare my informations and test my hypotheses.

## Data Collection

1. **Annual number of factories:**  
   - Provincial industrial status reports of the Ministry of Industry and Technology  
   - I will collect each year's report and find the number of factory establishments per year.  
   - Example report of 2021: [Link](https://www.sanayi.gov.tr/plan-program-raporlar-ve-yayinlar/81-il-sanayi-durum-raporlari/mu1602011640)  

2. **Harmful particles and chemical compounds:**  
   - Databank of the national air monitoring network of the Ministry of Environment, Urbanization and Climate Change.  
   - 2 different harmful particle diameters (PM10, PM2.5).  
   - 6 different chemical compounds (SO2, CO, NO2, NOX, NO, O3).  
   - Databank address: [Link](https://sim.csb.gov.tr/STN/STN_Report/StationDataDownloadNew)  

## Motivation

There are many factories in the neighborhood where I live in Istanbul and around the school where I study, and sometimes you can smell and see that the air is polluted. This made me wonder if there is a connection between air quality and the factories where we live, or what season of the year the air quality decreases.

## Dataset

**The dataset for this project consists of 2 different harmful particle diameter, 6 different chemical compounds and Number of factories per year. Here are the details:**

- **PM10**: Particles are defined by their diameter for air quality regulatory purposes. Those with a diameter of 10 microns or less are inhalable into the lungs and can induce adverse health effects.(µg/m3)
- **PM2.5**: Fine particulate matter is defined as particles that are 2.5 microns or less in diameter.(µg/m3)
- **SO2**: The largest source of SO2 in the atmosphere is the burning of fossil fuel that contains sulfur, such as coal or oil, in power plants and other industrial facilities.(µg/m3)
- **CO**: CO is a colorless, odorless gas that can be harmful when inhaled in large amounts. CO is released when something is burned. The greatest source of CO is  machinery that burn fossil fuels. (µg/m3)
- **NO2**: Nitrogen dioxide is a harmful gas. Refining of petrol and metals, commercial manufacturing, and food manufacturing, coal-burning appliances such as stoves, ovens, space and water heaters and fireplaces are the outdoor source of nitrogen dioxide.(µg/m3)
- **NOX**: Nitrogen oxides are produced in combustion processes, partly from nitrogen compounds in the fuel, but mostly by direct combination of atmospheric oxygen and nitrogen in flames. Nitrogen oxides are produced naturally by lightning, and also, to a small extent, by microbial processes in soils. (µg/m3)
- **NO**: Nitrogen monoxide is produced naturally by lightning and also to a small extent by microbial processes in the soil. The main sources of NO are combustion processes, partially from nitrogen compounds in fuel and from the direct combination of atmospheric oxygen and nitrogen in flames.(µg/m3)
- **O3**: Tropospheric or ground-level ozone – what we breathe – is formed primarily from photochemical reactions between two major classes of air pollutants, volatile organic compounds and nitrogen oxides (NOx).(µg/m3)

- **Number of factories per year**: Total number of factories in years.


## Analysis Plan
1. **Data Collection**
   - Importing the number of factories into Excel records.
   - Importing the chemical compounds into Excel records.
   - Importing the Excel records into a Pandas DataFrame and process the data.

2. **Visualization**
   - Visiualizing the datas as:
     - Correlation between number of factories in istanbul and chemical compounds.
     - Correlation between season of the year and air quality
    
3. **Hypothesis Testing**
   - Test hypotheses:
     - The increase in the number of factories in Istanbul over the years has reduced the air quality in the regions where factories are located in that areas.
     - Air quality in Istanbul is lower in cold months than in hot months.

4. **Trend Analysis**
   - Identifying peaks and plateus
   - Analyze how air quality in istanbul is related to the number of factories.

## Technologies and Tools
- **Python:** For statistical analysis
- **Pandas:** To process data
- **Machine Learning Model:** Linear Regression
 
