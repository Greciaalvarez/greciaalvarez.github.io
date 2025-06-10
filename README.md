##  **Bike Rental Analysis**
*Python Project by Grecia Zarella Alvarez Leyva*
### **1. Introduction**
The rental bike emerged strongly in 2020 during the pandemic, when people started to seek safer and more flexible ways to move around the city. Since then, it has become helpful among students and then among business professionals who value more convenience and sustainability options. Additionally, tourism and seasonal factors, especially the summer season, were key drivers of rental demand. Moreover, tourism destinations encourage renting and driving around the city as another way to do a personal tour. More cities are becoming greener in transportation, and rental companies wanting to develop and expand their business must keep an eye on rental trends. By aligning their strategies with these evolving consumer preferences and environmental shifts, companies can position themselves for long-term growth and consider expanding into emerging markets such as Latin America.

![image](https://github.com/user-attachments/assets/f12e8974-d03d-479d-b51b-6a648e0fad86)
![image](https://github.com/user-attachments/assets/ec5cad0a-65b3-4ff5-bd89-62bcb7c86eaa)

### **2. Insights**
#### **2.1 Insight One: "Growing Demand for Rental Bicycles"**
The bike rental business is growing, driven by consumers becoming more aware of environmental sustainability and seeking to avoid traffic congestion and harmful carbon emissions. Moreover, consumers found another way to save time and money. *According to Grand View Research (2024)*, the market is projected to grow at a rate of 16.8% from 2024 to 2030 in bikes and scooters. Being one of the major drivers is the demand for eco-friendly transportation and the desire to incorporate physical activity into daily routine, perfect exercises that consumers can find in traditional bikes and e-bikes (including motors). Today, bicycle rentals have become a trend, helpful among workers, business professionals, and students. They are very popular among tourists, finding it more convenient and flexible for getting around the city.
![image](https://github.com/user-attachments/assets/6cf1fa71-f216-4d42-a52d-2f6c1c24bd32)
![image](https://github.com/user-attachments/assets/a70ff068-4f20-41b2-932e-83e13662f0c6)
![image](https://github.com/user-attachments/assets/5f09facf-124b-4174-9587-2d045c814cbe)
![image](https://github.com/user-attachments/assets/badd9f71-6fe0-43fb-adb7-769046f4e6a9)
![image](https://github.com/user-attachments/assets/b18cd4ab-4d60-48c9-ac38-172e19a4dabd)
![image](https://github.com/user-attachments/assets/6ec44237-ab43-4203-b944-df0bc967a779)

### Seasonal Bike Rentals Analysis
This bar chart represents the total number of bike rentals for each season. After analyzing the data, we observed that most users tend to rent bikes in the Summer and Autumn, with 420,714 and 346,564 rentals, respectively. These results suggest that favorable weather conditions during these seasons encourage bike usage. Winter, however, contains the least number of rentals, which could be a result of low temperatures, rainfall, and wind speed. Autumn ranks second in total rentals, showing a steady volume regardless of holidays. The use of color allows easy distinction of seasonal trends, effectively making the visualization a quick comparison of seasonal rental patterns. This insight can help rental bike companies to enhance their marketing strategies during the year.

#### **2.2 Insight Two: "Ideal Weather Conditions for Bike Rental Demand"**
Based on a recent study in Seoul, South Korea *(Jang et al.,2024)* confirms the relation between rental bikes and weather conditions as a factor to significantly impacts the rental demand for bikes. Their study reflects that through the exploration of the dataset and establishment relationship between variables, the key features to drive the demand for rental bikes include temperature, humidity, wind speed, visibility, solar radiation, rainfall, snowfall, hours of the day, season, and holidays. The study concluded that temperature, wind speed, and rainfall were the most affecting factors. The highest number of rentals resulted from days with warm temperatures and no rain. Even though this research is specific to Seoul, it resonates with our overall trend seen in our dataset. Riders prefer to rent bikes in hot, dry, and comfortable weather conditions.

![image](https://github.com/user-attachments/assets/67c3ba21-2f07-4e28-9111-10d3e5b26aa0)
![image](https://github.com/user-attachments/assets/0b40a55b-eda9-450e-9175-8eb875e92f34)
#### Code Analysis
To develop Insight Two, we first identified descriptive statistics to understand the overall information and basic numerical patterns. Then we narrowed the analysis by selecting specific variables such as temperature, wind speed, and rainfall that could impact bike rental demand. Finally, we examined the correlation among key factors to understand the positive or negative influence on rental behavior as well as the ideal weather conditions.
![image](https://github.com/user-attachments/assets/52c0cdf6-7de1-464e-bf07-2bba5d8da559)
![image](https://github.com/user-attachments/assets/66cb75d0-0065-4404-929c-126a6f5c8d75)

#### Linear Correlation Heatmap for Weather Conditions and Rentals Analysis

The present heatmap shows the linear correlation between key weather variables and the number of bike rentals. The source and insight reveal that the main key variables that affect the demand for rental bikes are Temperature, Wind Speed, and Rentals. The heatmap reflects a moderate positive correlation between temperature and rentals (0.55), meaning that warm weather encourages users to choose biking as an alternative transportation. In contrast, rainfall (-0.11) and wind speed (-0.12) show a negative correlation, meaning that bad weather conditions discourage bike use. This analysis shows that warm weather conditions play a critical role in the total demand. Overall, the graph highlights the importance of weather in rental business operations planning.

![image](https://github.com/user-attachments/assets/99688700-4032-4e71-837d-1a0c4c68d300)
![image](https://github.com/user-attachments/assets/75170d29-6b2d-4c6d-b7ab-09b7f2a8a3f5)

#### Bike Rentals by Hour of the Day Analysis
The scatter plot shows the distribution between the range of hours during the day and the number of rentals. The visualization shows two important peaks: one at 8 AM and the other at 5 – 6 PM. These peaks represent morning and evening rush hours, which means that a majority of users utilize bikes as a mode of transportation from school or work. Midday hours have moderate activity, usual to local activities, and short distances. On the other hand, rentals fall significantly after 11 pm and continue until early hours of the next day. This graph shows the cyclical demand for bicycles in a day. Companies can use this information to optimize bike availability and maintenance scheduling throughout the day. Overall, after 3 pm, the bike demand starts to go up, also due to tourist consumption.
#### **2.3 Insight Three: "The Future of Mobility"**
According to the McKinsey report identifies how urban mobility is shifting towards more sustainable and alternative transport, with micromobility like bicycles and e-scooters being an important contributor. The report states that 60–70% of urban journeys could be replaced with micromobility solutions over the short term. As cities look for emission reduction and decongestion, demand for bicycle rental systems will rise globally. 
This report emphasizes that Asia, Europe, and North America are leading this trend, but indicates that there are other potential emerging regions like Latin America. However, this trend supports the expansion of rental bikes as a key part of a smart, clean, and accessible transportation system shortly.
### **3. References**
Grand View Research. (2024). *Bike & scooter rental market size, share & trends analysis report by vehicle type, by application, by region, and segment forecasts, 2024–2030.* https://www.grandviewresearch.com/industry-analysis/bike-scooter-rental-market-report

Jang, H., Lee, Y., & Park, J. (2024). *Short-term demand forecasting for bike-sharing systems using machine learning techniques: A case study in Seoul. Smart Cities and Society.* https://doi.org/10.1016/j.scsoc.2024.100105

Woetzel, J., Baig, F., Choi, W., Garemo, N., Mischke, J., & Poh, F. (2019, February 25). *The future of mobility: How transportation is evolving. McKinsey & Company.* https://www.mckinsey.com/industries/automotive-and-assembly/our-insights/the-future-of-mobility-mobility-evolves

 ### **4. Analysis Questions**

 1. **Why are the majority of users renting bicycles?**
According to the dataset, the majority of users rent bicycles during June, on Thursday, specifically in the summer season, and this trend happens on non-holidays. These variables represent the most frequent values in the data, highlight a clear pattern in the consumer behavior. Summer is the season with the highest total number of rentals (420,714), followed by Autumn (346,564). This insight suggests that while Autumn and Spring represent a significant number of rentals, the Summer season has a strong demand, due to good weather, school vacations or tourism. Additionally, the preferences for renting bikes on regular weekdays and non-holidays indicate that bike rentals are commonly used for routine activities as commuting or local activities.
   
 2. **Are there ideal weather conditions that create high bike rental demand? If so, what are they?**
The dataset and insight show that there are ideal weather conditions that influence the high demand for rental bikes. Most users prefer to rent bikes in dry, sunny, and warm conditions, when the weather is typically warmer and more comfortable for outdoor activities. These align with the most rental numbers happening in Summer, especially in June, with holidays, school vacations, and tourism increasing outdoor activity. Therefore, high temperatures and low rainfall appear to be ideal weather factors that drive up the demand for bike rentals. This is further supported by a positive correlation of 0.55 between Temperature and Rentals, and a negative correlation of -0.11 between Rainfall and Rentals.
   
 3. **How should the company strategize based on your results? In other words, what actionable steps can the company take in order to take advantage of your insights?**
Based on insights from data, the company must prioritize its operations and marketing during the summer season, when there are the highest demand for bike rentals occurs, especially in June. Initiative must be focused on cities and holiday locations with ideal weather conditions, such as warm temperatures and low rainfall, because these foster more rentals. Since most riders rely on rental bikes for daily transportation, weekday supply and value-priced commuter packages must be marketed by the company. Moreover, there are opportunities to expand in underpenetrated markets, primarily in Latin America, where the rental bike is underdeveloped due to rising urban populations. Investment in tourist campaigns and infrastructure partnerships in these markets can drive long-term growth and brand recognition.

### **5. Conclusion**
In summary, rental bicycle demand is driven by reasons such as commuting, especially among professionals and students, and lifestyle-related factors such as tourism and seasonal outdoor activities. The trend reflects growing popularity for sustainable, convenient, and flexible transport. The analysis of the dataset, insight, and credible sources shows that favorable warm weather, as summer promotes higher rental activity, indicating seasonality. As reported in recent case studies and serious reports, the micromobility sector will continue to grow, opening up promising growth opportunities for rental companies. To stay competitive, these companies should align their approaches with shifting consumer behavior and target new markets, especially in fast-growing markets like Latin America, where the growth potential is still changing. 
