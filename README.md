# **Exploratory Data Analysis Project 1 (Indian Energy Production)** 

## **Introduction**
"India is the world's third-largest producer and third largest consumer of electricity. The national electric grid in India has an installed capacity of 370.106 GW as of 31 March 2020. Renewable power plants, which also include large hydroelectric plants, constitute 35.86% of India's total installed capacity.
India has a surplus power generation capacity but lacks adequate distribution infrastructure.ndia's electricity sector is dominated by fossil fuels, in particular coal, which during the 2018-19 fiscal year produced about three-quarters of the country's electricity.The government is making efforts to increase investment in renewable energy. The government's National Electricity Plan of 2018 states that the country does not need more non-renewable power plants in the utility sector until 2027, with the commissioning of 50,025 MW coal-based power plants under construction and addition of 275,000 MW total renewable power capacity after the retirement of nearly 48,000 MW old coal-fired plants."

## **Data Sourcing/Credits**
The dataset used for this project can be found on Kaggle, **"Daily Power Generation in Indian (2017 - 2020)"**. This dataset was created by users **"Navin"** and **"Twinkle Khanna"**.  

### **Objectives:**
- Perform exploratory data analysis on the data set to find key insights.
- Perform data cleaning and data structuring to ensure data set is in good condition to work with.
- Create appealing graphs and images using Python that highlight findings and point out trends and patterns.

## **Data Description**
- **Date**: date in YYYY-MM-DD format.
- **Thermal Generation Actual (in MU)**: amount of **actual** thermal energy generated, measured in MU (gigawatt-hours).
- **Thermal Generation Estimated (in MU)**: amount of **expected/estimated** thermal energy generated, measured in MU.
- **Nuclear Generation Actual (in MU)**: amount of **actual** nuclear energy generated, measure in MU.
- **Nuclear Generation Estimated (in MU)**: amount of **expected/estimated** nuclear energy generated, measured in MU.
- **Hydro Generation Actual (in MU)**: amount of **actual** hydro-electrical energy generated, measured in MU.
- **Hydro Generation Estimated (in MU)**: amount of **expected/estimated** hydro-electrical energy generated, measured in MU.
- **Region**: which region of Indian (Nother, Western, Southern, Eastern, and NorthEastern).

## **Exploratory Data Analysis**

- This plot shows energy production over time for each energy type after data has been resampled from a daily format to a monthly format, making the plot easier to read compared to the original.
  - We can clearly see that 'Thermal' energy is the most widely produced, with 'Hydro' coming in second. This aligns with the historical data given with the data set. We also notice that 'Nuclear' energy is used **20x less** than 'Thermal'.
  
![(Plot 2) Time Series Resampled Data](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/ad638e38-b06a-4e44-94bc-b2361c276905)

- This plot visualizes the relationship between energy production and region.
  - We notice that the 'Western' region is by far the largest producer of 'Thermal' energy, whereas the 'Northern' region is the highest producer of 'Hydro' energy. We also notice that the 'Southern' region is the leader in terms of 'Nuclear' energy production and that both the 'Easter' and 'NorthEastern' regions do not produce any 'Nuclear' energy at all.

![(Plot 3) Power Generation by Region](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/e90b2400-a087-414b-a5b8-79fbdd3481b0)

- The plot below visualizes **actual** energy production from September 2017 to August 2020.

![(Plot 4) Total Energy Production Over Time](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/66a64d6f-76b9-435e-80f0-77f05ae62752)

- The following plot visulizes **actual** 'Thermal' energy production by region from September 2017 to August 2020. 

![(Plot 5) Thermal Production Over Time](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/7697b639-05c9-493d-a752-ec535e67aa5a)

- The plot below visulizes **actual** 'Nuclear' energy production by region from September 2017 to August 2020.

![(Plot 6) Nuclear Production Over Time](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/a3e91943-85a3-46a4-a01f-4eaa147e841b)

- This plot visulizes **actual** 'Hydro' energy production by region from September 2017 to August 2020.
  - In this plot we notice a clear seasonal trend in energy production most likely do to weather conditions that may impact water amounts (rain seasons, droughts, etc.).

![(Plot 7) Hydro Production Overtime](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/59656abb-ce9e-4891-ae0e-a147f14b6b1a)

- From the second data set that contains 'State_Region' data we created a pie chart that visualizes national share of energy production by region.
  - This graph restates the findings from the above plots.

![(Plot 8) Power Generation by Region](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/1475db3f-03d4-4b83-bfe8-98632b555825)

- Also from the second data set we created a pie chart that visualizes energy production by state.

![(Plot 9) Energy Production by State](https://github.com/tobi-soboyejo/eda1_indian_energy/assets/155042996/d7357d40-0cf4-44aa-91b8-dc89bfd3f4d9)


