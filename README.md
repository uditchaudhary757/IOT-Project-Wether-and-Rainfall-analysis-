# IOT-Project-Wether-and-Rainfall-analysis-


# WEATHER TRENDS & RAINFALL ANALYSIS
### A 10-Year Climate Data Study of Bareilly, Uttar Pradesh (2016–2025)

**Project Group:** BCA_AI_08  
**Project ID:** DA-008  
**Programme:** BCA Artificial Intelligence  
**Semester:** First Year – Semester I  
**Section:** B  
**Project Mentor:** Mahendra  

---

# 1. Introduction and Project Overview

Weather Trends & Rainfall Analysis – Bareilly (2016–2025) is an IoT-oriented environmental monitoring and climate-data analytics project developed to study and visualize the weather patterns of Bareilly, Uttar Pradesh, over a period of ten years.

The project focuses primarily on two important climatic parameters:

1. Annual Rainfall (Precipitation), measured in millimetres (mm).
2. Annual Mean Temperature, measured in degrees Celsius (°C).

The main objective is to understand how rainfall and temperature have varied over the selected decade, identify the wettest and driest years, examine seasonal rainfall distribution and present the findings through an interactive web-based analytics dashboard.

Traditional weather information is often available in separate reports, tables and weather-data platforms. Understanding long-term variations requires users to collect information from different sources and manually compare values.

Our project simplifies this process by bringing important weather information together in one centralized dashboard.

The dashboard, called **Bareilly Weather Analytics**, provides an interactive interface containing annual rainfall charts, temperature comparisons, monthly rainfall patterns, seasonal breakdowns, climate anomaly information and environmental sensor monitoring.

An additional feature is the IoT-based live sensor monitoring section. It demonstrates how a weather station equipped with environmental sensors could collect and transmit real-time weather information to a centralized dashboard.

The current prototype uses Python-generated simulated sensor readings. Physical sensor integration through ESP32 or Arduino is planned as a future enhancement.

By combining historical climate information, data analytics, visualization and IoT concepts, the project demonstrates how technology can make environmental information easier to understand and explore.

# 2. Problem Statement

Weather and climate information play an important role in agriculture, environmental planning, water management and everyday decision-making.

However, understanding weather variations over several years can be difficult when information is distributed across different sources and presented mainly in numerical tables.

Some major challenges include:

1. **Scattered Weather Information:** Historical rainfall and temperature information may be available across different websites, reports and datasets.

2. **Difficulty in Comparing Years:** Identifying the wettest and driest years requires organizing and comparing annual rainfall records.

3. **Understanding Rainfall Variations:** Annual rainfall can change considerably from one year to another, making it important to examine historical variations.

4. **Temperature Analysis:** Understanding whether annual mean temperature changes significantly or remains relatively stable requires year-wise comparison.

5. **Seasonal Rainfall Distribution:** Annual rainfall totals do not explain when rainfall occurs. Understanding the contribution of different seasons is equally important.

6. **Limited Environmental Monitoring:** Historical climate datasets do not provide the same functionality as a live environmental monitoring system.

7. **Lack of Visual Analytics:** Numerical information alone may not clearly communicate weather trends to students, researchers and general users.

### Proposed Solution

Our project proposes a centralized weather analytics dashboard that organizes historical climate information for Bareilly from 2016 to 2025.

The platform presents annual rainfall, annual mean temperature, seasonal rainfall distribution and monthly patterns through interactive charts and summary cards.

It also includes an IoT-oriented sensor monitoring interface that demonstrates how environmental readings can be displayed through a connected application.

This approach makes weather information more accessible, organized and understandable.

# 3. Objectives of the Project

The primary objective is to analyze ten years of rainfall and temperature information for Bareilly and develop an interactive dashboard for presenting the results.

The specific objectives are:

- To study annual rainfall patterns between 2016 and 2025.
- To analyze annual mean temperature variations.
- To identify the wettest and driest years.
- To calculate and present average annual rainfall.
- To calculate and present average annual temperature.
- To compare rainfall variation with temperature variation.
- To understand seasonal rainfall distribution.
- To visualize monthly rainfall patterns.
- To develop an interactive weather analytics dashboard.
- To provide filtering functionality for selecting the analysis period.
- To demonstrate IoT-based environmental monitoring.
- To display temperature, humidity, rainfall, soil moisture and water-level readings.
- To explore how ESP32 or Arduino hardware could be integrated into the system.
- To identify unusual climatic observations through an anomaly-monitoring interface.
- To encourage data-driven understanding of local environmental conditions.

# 4. Project Scope

The project focuses on the geographical location of Bareilly, Uttar Pradesh, India.

### Geographical Scope
Bareilly, Uttar Pradesh, India.

The geographical reference represents an approximate city-centre grid.

### Time Scope
Ten calendar years:

2016–2025.

### Main Variables

| Parameter | Measurement Unit |
|---|---|
| Annual Rainfall | Millimetres (mm) |
| Mean Temperature | Degrees Celsius (°C) |
| Humidity | Percentage (%) |
| Soil Moisture | Percentage (%) |
| Water Level | Appropriate distance or level units |

The first two parameters form the main historical climate analysis, while the remaining parameters are included in the IoT sensor-monitoring demonstration.

# 5. Technologies Used

The project combines web development, backend processing, data analysis and IoT concepts.

### 5.1 HTML – HyperText Markup Language

HTML provides the structural foundation of the weather analytics website.

It is responsible for:
- Creating dashboard sections.
- Organizing headings and content.
- Displaying sensor information.
- Creating data tables.
- Structuring navigation components.
- Providing containers for graphs and charts.

### 5.2 CSS – Cascading Style Sheets

CSS is used to design and style the dashboard.

Its responsibilities include:
- Dashboard layout.
- Background and colour styling.
- Cards and information panels.
- Typography.
- Spacing and alignment.
- Responsive interface design.
- Visual presentation of weather information.

### 5.3 JavaScript

JavaScript provides interactive functionality to the website.

It supports:
- Dashboard interactions.
- Chart rendering and updates.
- Filter interactions.
- Dynamic presentation of information.
- Communication with backend endpoints where implemented.

### 5.4 Python

Python is used for backend processing and data-related operations.

It supports:
- Weather-data processing.
- Statistical calculations.
- Generation of simulated sensor readings.
- Preparation of information for dashboard display.
- Backend application logic.

### 5.5 Flask

Flask is a lightweight Python web framework used to run the weather analytics application.

The application runs locally through a Python server at:

127.0.0.1:5000

Flask provides the backend environment through which the dashboard can access processed information.

### 5.6 Pandas

Pandas is a Python library used for organizing and processing structured data.

It is suitable for:
- Organizing year-wise weather records.
- Working with rainfall and temperature datasets.
- Calculating averages.
- Comparing annual values.
- Preparing data for analysis.

### 5.7 Chart.js

Chart.js is used to create graphical representations of weather information.

It supports:
- Annual rainfall bar charts.
- Seasonal rainfall doughnut charts.
- Monthly rainfall distribution charts.
- Rainfall and temperature comparison charts.

### 5.8 IoT Hardware Concepts

The proposed physical weather-monitoring system includes:

- ESP32 or Arduino controller.
- Temperature and humidity sensor.
- Rain gauge.
- Soil moisture sensor.
- Water-level sensor.

These components represent the planned hardware architecture. The current dashboard uses simulated readings rather than physically connected sensors.

# 6. Historical Weather Data Analysis (2016–2025)

This is the primary analytical component of the project.

The study examines ten years of annual rainfall and mean temperature information for Bareilly.

### 6.1 Annual Rainfall Analysis

Rainfall is measured in millimetres.

The project presentation reports the following annual rainfall values:

| Year | Annual Rainfall |
|---|---:|
| 2016 | 1,069 mm |
| 2017 | 939 mm |
| 2018 | 1,265 mm |
| 2019 | 951 mm |
| 2020 | 1,009 mm |
| 2021 | 1,219 mm |
| 2022 | 903 mm |
| 2023 | 1,062 mm |
| 2024 | 1,071 mm |
| 2025 | 1,175 mm |

### Important Findings

**Wettest Year: 2018**

2018 recorded the highest annual rainfall in the supplied dataset, with 1,265 mm.

**Driest Year: 2022**

2022 recorded the lowest annual rainfall, with 903 mm.

**Average Annual Rainfall:**

The presentation reports a decade average of approximately 1,066 mm per year.

**Rainfall Range:**

1,265 − 903 = 362 mm.

This means that the difference between the highest and lowest annual rainfall totals was 362 mm.

These findings demonstrate considerable variation in annual rainfall during the selected period.

### 6.2 Annual Mean Temperature Analysis

The second major parameter is annual mean temperature.

The project uses the following values:

| Year | Mean Temperature |
|---|---:|
| 2016 | 26.3 °C |
| 2017 | 26.3 °C |
| 2018 | 25.8 °C |
| 2019 | 25.5 °C |
| 2020 | 25.1 °C |
| 2021 | 25.1 °C |
| 2022 | 25.7 °C |
| 2023 | 25.3 °C |
| 2024 | 25.8 °C |
| 2025 | 25.2 °C |

### Important Findings

- Highest annual mean temperature: 26.3 °C.
- Lowest annual mean temperature: 25.1 °C.
- Highest values occurred in 2016 and 2017.
- Lowest values occurred in 2020 and 2021.
- Reported decade average: 25.6 °C.

**Temperature Range:**

26.3 − 25.1 = 1.2 °C.

The annual mean temperature therefore remained within a comparatively narrow range during the selected decade.

### 6.3 Rainfall and Temperature Comparison

One important part of the project is comparing annual rainfall and annual mean temperature.

The dashboard uses a combined chart:

- Bars represent annual rainfall.
- A line represents annual mean temperature.

This makes it possible to compare the two variables visually.

The analysis shows that rainfall varies more widely than annual mean temperature.

However, the available ten-year data does not establish a strong relationship between the two variables.

# 7. Seasonal Weather Analysis

Weather conditions vary throughout the year.

The project uses the India Meteorological Department's Bareilly climatological reference for explaining the typical seasonal pattern.

The year is divided into four broad seasons.

### 7.1 Winter Season (January–March)

During this period, rainfall is generally lower than during the monsoon season.

Temperature conditions are comparatively cooler.

### 7.2 Pre-Monsoon Season (April–June)

This period is generally characterized by increasing temperatures.

May is commonly the hottest month.

Rainfall can begin increasing toward the arrival of the monsoon.

### 7.3 Monsoon Season (July–September)

This is the most important rainfall period for Bareilly.

A major proportion of annual precipitation occurs during these months.

The project dashboard represents the monsoon as the largest contributor in its seasonal rainfall distribution chart.

### 7.4 Post-Monsoon Season (October–December)

Rainfall generally decreases after the monsoon season.

The weather gradually transitions toward the winter period.

**Important:** The seasonal descriptions are based on IMD climatological context for 1991–2020. They are not separate verified seasonal measurements for every year from 2016 to 2025.

# 8. IoT-Based Environmental Monitoring System

This is the main IoT component of the project.

The project includes an environmental monitoring interface designed to demonstrate how a smart weather station can collect information from different environmental sensors and display it on a centralized dashboard.

The proposed system uses a microcontroller such as ESP32 or Arduino to connect environmental sensors.

### 8.1 Temperature Monitoring

A temperature sensor measures the surrounding atmospheric temperature.

The proposed DHT sensor can measure temperature and provide readings to the controller.

The dashboard includes a temperature monitoring tile.

### 8.2 Humidity Monitoring

Humidity represents the amount of moisture present in the air.

A DHT sensor can also measure relative humidity.

Humidity information can help users understand atmospheric moisture conditions.

### 8.3 Rainfall Monitoring

A rain gauge is proposed for measuring rainfall.

In a physical implementation, the rainfall sensor would generate measurements that could be processed by the controller and transmitted to the dashboard.

Rainfall readings are generally expressed in millimetres.

### 8.4 Soil Moisture Monitoring

A soil moisture sensor measures the moisture content of soil.

This parameter is particularly useful in agricultural applications.

It can help demonstrate how environmental monitoring systems can provide information about soil conditions.

### 8.5 Water-Level Monitoring

An ultrasonic sensor is proposed for monitoring water levels.

It can measure the distance between the sensor and the water surface.

With suitable installation and calibration, this measurement can be converted into an estimated water level.

This feature could be useful for monitoring water-storage systems and selected environmental applications.

### Current Implementation

The five sensor categories are represented in the dashboard.

However, the current prototype generates simulated readings using Python.

Physical sensors and ESP32/Arduino hardware are planned for future integration.

# 9. Project Workflow

The project follows a five-stage workflow.

### Stage 1: Environmental Data Collection

Weather information is collected from published climate-data sources.

The proposed physical system would also collect readings through:
- Temperature sensors.
- Humidity sensors.
- Rain gauges.
- Soil moisture sensors.
- Water-level sensors.

Current status: Historical dataset-based analysis and simulated sensor demonstration.

### Stage 2: Microcontroller

The proposed hardware architecture includes an ESP32 or Arduino board.

The controller would receive information from the connected sensors.

Current status: Planned.

### Stage 3: Data Logging

Weather information is organized into a structured dataset.

Historical data is maintained year-wise for rainfall and temperature analysis.

Future sensor integration would allow timestamped environmental readings to be stored.

### Stage 4: Data Analysis

The application processes weather information.

It performs:
- Annual rainfall comparison.
- Temperature comparison.
- Average calculations.
- Wettest and driest year identification.
- Seasonal analysis.
- Trend visualization.

Current status: Working.

### Stage 5: Interactive Dashboard

The final stage presents the analyzed information through a web interface.

Users can explore:
- Weather statistics.
- Annual rainfall charts.
- Temperature comparisons.
- Seasonal patterns.
- Monthly distributions.
- Sensor monitoring tiles.
- Climate anomaly information.

Current status: Working prototype.

# 10. Dashboard Features and Functionalities

The project includes an interactive dashboard called Bareilly Weather Analytics.

It runs locally through a Flask server.

The dashboard is divided into several sections.

### 10.1 Dashboard Overview

The main dashboard provides a summary of the weather information.

It includes:
- Project title.
- Analysis period filter.
- Four KPI cards.
- IoT monitoring panel.
- Weather analytics sections.

The KPI cards represent:
1. Average Rainfall.
2. Peak Monsoon Year.
3. Driest Year.
4. Monsoon Share.

These cards provide a quick overview of the selected climate dataset.

### 10.2 Period Filter

The dashboard includes a filter that allows users to select the analysis period.

This makes it easier to focus on particular years rather than viewing the complete decade every time.

### 10.3 IoT Live Sensor Panel

The sensor monitoring panel displays five environmental parameters:

| Sensor Category | Measurement |
|---|---|
| Temperature | Atmospheric temperature |
| Humidity | Air moisture |
| Rainfall | Precipitation |
| Soil Moisture | Soil water content |
| Water Level | Water-level measurement |

The panel demonstrates the proposed real-time monitoring interface.

The current values are simulated by Python.

### 10.4 Annual Precipitation Chart

This chart displays rainfall totals for every year from 2016 to 2025.

The visualization uses contrasting colours to highlight:
- The wettest year.
- The driest year.
- Other annual rainfall values.

It makes year-wise comparison easier.

### 10.5 Seasonal Rainfall Distribution

A doughnut chart displays the distribution of rainfall across four seasons:

- Winter.
- Pre-Monsoon.
- Monsoon.
- Post-Monsoon.

The monsoon section represents the largest share in the dashboard's seasonal visualization.

### 10.6 Monthly Rainfall Distribution

This chart presents rainfall patterns from January to December.

The dashboard illustrates how rainfall generally increases around May and reaches its highest levels during July and August.

This visualization helps users understand the seasonal nature of rainfall.

### 10.7 Rainfall and Temperature Comparison

A dual-axis chart compares:
- Annual rainfall using bars.
- Annual mean temperature using a line.

Separate axes are important because rainfall and temperature use different measurement units.

This chart provides a combined view of annual climate variations.

### 10.8 Climate Anomalies and Extreme Events

The dashboard includes a climate anomaly table.

It contains four main columns:

1. Year.
2. Event Classification.
3. Impact Summary.
4. Severity Index.

Colour-coded severity indicators help distinguish different levels of events.

The current entries are prototype examples and require verification against official weather-station records before being treated as actual historical events.

### 10.9 Raw Data View

The raw-data section provides access to the underlying weather information in a structured format.

It helps users examine the numerical values used in the analysis.

### 10.10 Presentation Deck

The dashboard also includes a presentation-oriented view.

This provides a convenient way to display the project's main findings and visualizations during demonstrations.

# 11. Data Collection and Sources

The historical climate information is based on published data sources.

### 11.1 WeatherBlaze

The project's year-wise rainfall and temperature figures are taken from the WeatherBlaze Bareilly weather-history overview.

The overview identifies NASA POWER / MERRA-2 as its climate-data sources.

### 11.2 NASA POWER

NASA POWER stands for Prediction Of Worldwide Energy Resources.

It provides gridded, model-based environmental and climate information.

The project's historical climate values are described as gridded estimates rather than direct measurements from a single rain gauge installed in Bareilly.

### 11.3 India Meteorological Department (IMD)

The India Meteorological Department's Bareilly climatological reference is used to understand typical seasonal weather patterns.

It provides background information about:
- Seasonal rainfall.
- Temperature variations.
- Monsoon patterns.
- Typical monthly weather conditions.

The IMD's 1991–2020 climatological reference is used separately from the 2016–2025 annual dataset.

# 12. System Architecture

The project can be divided into four major layers.

### Layer 1: Environmental Input Layer

This layer represents the environmental information collected from:
- Temperature sensors.
- Humidity sensors.
- Rain gauges.
- Soil moisture sensors.
- Water-level sensors.

In the current prototype, sensor values are simulated.

### Layer 2: Controller and Communication Layer

This layer represents the proposed ESP32 or Arduino controller.

The controller would receive sensor readings and transmit the information to the application.

Physical integration is planned.

### Layer 3: Backend and Data Processing Layer

Python and Flask provide the backend environment.

This layer handles:
- Processing historical weather information.
- Preparing sensor data.
- Performing calculations.
- Organizing information for visualization.

### Layer 4: Dashboard and Visualization Layer

The frontend presents the processed information.

HTML, CSS, JavaScript and Chart.js are used to display the results through:
- Statistical cards.
- Graphs.
- Tables.
- Sensor monitoring panels.
- Interactive dashboard components.

# 13. Applications of the Project

The proposed system has several potential applications.

### 13.1 Agricultural Monitoring

Rainfall and soil moisture information can help farmers understand environmental conditions relevant to agricultural planning.

### 13.2 Environmental Monitoring

The project demonstrates how different environmental parameters can be monitored through a centralized platform.

### 13.3 Rainfall Analysis

Historical rainfall comparisons can help users understand variations in precipitation over different years.

### 13.4 Water Resource Management

Rainfall and water-level monitoring can support awareness of water availability and storage conditions.

### 13.5 Educational Research

Students can use the dashboard to understand climate data, statistical comparisons, IoT concepts and data visualization.

### 13.6 Local Climate Awareness

The project provides a centralized interface for exploring historical weather information about Bareilly.

# 14. Results and Major Findings

The project produced several important findings from the supplied ten-year dataset.

| Parameter | Result |
|---|---|
| Study Location | Bareilly, Uttar Pradesh |
| Study Period | 2016–2025 |
| Mean Annual Rainfall | 1,066 mm |
| Mean Annual Temperature | 25.6 °C |
| Wettest Year | 2018 |
| Wettest Year Rainfall | 1,265 mm |
| Driest Year | 2022 |
| Driest Year Rainfall | 903 mm |
| Rainfall Range | 362 mm |
| Highest Mean Temperature | 26.3 °C |
| Lowest Mean Temperature | 25.1 °C |
| Temperature Range | 1.2 °C |

The findings indicate that annual rainfall varied considerably more than annual mean temperature during the selected period.

The dashboard successfully demonstrates how historical weather information can be organized and presented through interactive visualizations.

It also demonstrates the proposed integration of environmental sensor monitoring into the same platform.

# 15. Limitations of the Current Project

The project is an educational prototype and has some limitations.

1. The physical weather-station sensors are not yet connected.
2. The live IoT readings are simulated using Python.
3. ESP32/Arduino integration is planned rather than currently operational.
4. Historical climate values are gridded estimates and may differ from official local rain-gauge observations.
5. The study covers only ten years, which is insufficient by itself to establish a long-term climate trend.
6. Some dashboard KPI and chart values are prototype/sample values and need reconciliation with the presentation dataset.
7. The climate anomaly table contains demonstration entries that require verification.
8. The project is not a validated live weather-forecasting or emergency early-warning service.

Recognizing these limitations is important for maintaining scientific accuracy.

# 16. Future Scope

The project has considerable potential for further development.

### 16.1 Physical Sensor Integration

The first major enhancement would be connecting actual environmental sensors to an ESP32 or Arduino controller.

### 16.2 Real-Time Weather Monitoring

The system could be upgraded to display actual temperature, humidity and rainfall readings.

### 16.3 Wireless Data Transmission

Communication technologies could be implemented to transmit sensor readings from the weather station to the dashboard.

### 16.4 Database Integration

A database could be introduced to maintain historical and real-time environmental readings with timestamps.

### 16.5 Advanced Weather Analytics

Additional analytics could be introduced to identify:
- Seasonal variations.
- Unusual rainfall patterns.
- Changes in temperature.
- Long-term environmental patterns.

### 16.6 Weather Notifications

The system could generate notifications when selected environmental parameters cross configured thresholds.

Such notifications would be informational and would require proper validation before being used for operational warnings.

### 16.7 Improved Data Accuracy

Historical climate estimates could be compared against official IMD station observations.

### 16.8 Mobile-Friendly Dashboard

The dashboard could be extended into a mobile application or Progressive Web Application.

### 16.9 Data Export

Users could be provided with downloadable CSV or PDF reports containing weather statistics and analytical results.

### 16.10 Advanced Predictive Analytics

After collecting sufficient reliable historical observations, future versions could explore statistical forecasting or machine-learning models for rainfall and temperature analysis.

These capabilities are proposed enhancements, not features of the current implementation.

# 17. Conclusion

Weather Trends & Rainfall Analysis – Bareilly (2016–2025) is an environmental analytics project that combines historical climate-data analysis, web development, data visualization and IoT-based monitoring concepts.

The project studies ten years of rainfall and annual mean temperature information to understand the climatic variations of Bareilly.

The analysis identifies 2018 as the wettest year, with 1,265 mm of rainfall, and 2022 as the driest year, with 903 mm. It also demonstrates that annual mean temperature remained within a comparatively narrow range of 25.1 °C to 26.3 °C.

The interactive Bareilly Weather Analytics dashboard makes this information accessible through summary cards, annual rainfall charts, temperature comparisons, monthly rainfall patterns, seasonal breakdowns and climate anomaly tables.

The IoT monitoring component introduces the concept of a smart weather station by demonstrating how temperature, humidity, rainfall, soil moisture and water-level readings can be displayed on a centralized platform.

Although physical sensor integration is still planned, the current prototype provides a foundation for developing a more advanced environmental monitoring system.

Overall, the project demonstrates how data analytics and IoT technology can be combined to improve the understanding and presentation of local weather information.

**Project Vision: Understand Weather Patterns, Monitor Environmental Conditions and Build a Smarter Approach to Climate Awareness.**
