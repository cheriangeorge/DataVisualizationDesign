[Link to Assignment](https://github.com/bsc-iitm/Data-Visualization-Design-CS4001/issues/8)


### Title :  [Data | From 5% to 15%, China’s share in India’s imports tripled in last two decades](https://www.thehindu.com/data/data-from-5-to-15-chinas-share-in-indias-imports-tripled-in-last-two-decades/article66429612.ece) 
Article by [JASMIN NIHALANI](https://www.thehindu.com/profile/author/Jasmin--Nihalani-15087/)
Date of Publication : January 27, 2023 07:49 am | Updated January 28, 2023 12:06 am IST

#### Story 
The author uses India's trade data(import-export by value) from 2002 to 2022 to highlight the increase in imports from China to India over two decades. The author also highlights the decline in India's exports to China from 2020 (6.9%) to 2022 (3.4%). However during the same period (2002 to 2022) India's exports to China do not show a consistent trend as in the case of imports. The author uses two charts to show the trade deficit between the two countries widening between 2002 and 2022. 

The story also looks at the change in imports between China and 9 other countries including India between 2011 and 2021. A slope chart is used to illustrate this difference. The chart indicates and increase in imports from China for 8 countries while US remains constant. 

The story also explores the types of commodities imported by India from China and exported from India to China. While non-value added raw materials constitute most of India's exports to China, India's imports primarily constitute finished electronic goods and machinery with a high degree of value addition. The author uses 2 tree-map charts to represent this. Line charts have also been used to capture the dependency of India on China for 5 types of goods/commodities from 2012 to 2021
 
##### Data Sources used in the story
- [UN Comtrade Database](https://comtrade.un.org/data/) 
- [Ministry of Commerce and Industry](https://commerce.gov.in/trade-statistics/)

The original data used for the story was downloaded from the above 2 sources. India's net import / export values for the years 2002 - 2022 were also taken. This is not represented in the original story. 

Type of data : International Trade data from 2002 to 2022 
Extent of data : Yearly aggregates of imports and exports between countries. Net trade data and commodity wise break up are available
Dimensions of data : 2 dimensional in most cases - value of trade and year are the dimensions available in the data. In one of the data visualisations a geographical dimension has also been used. This can be seen in the third figure below. 
Gaps in the Data : The original story misses out India's net exports and imports by year and considers only the imports and exports between India and China. A line chart indicating the change in percentage of imports and exports between India and China from 2002 to 2022 has be represented in the chart.
Essential Data : India-China trade by value, commodity wise data
Irrelevant Data : Item-wise dependency data does not really contribute to the narrative put forth.

##### Visualisation 1
###### Imports from China to India
|  Original Visualisation |  Modified Visualisation |
|---|---|
|  ![Screenshot from 2023-03-14 23-19-30](https://user-images.githubusercontent.com/3922260/226202824-358433a6-54da-432f-b9d9-94319e4bcab7.png)  |  ![Imports from China to India](https://user-images.githubusercontent.com/3922260/226203055-cbb5afdd-f491-484b-9ad2-47cf4899279b.png)  |
* Click to enlarge above visualisations

The original visualisation uses import data (China to India) in $ billion from 2002 to 2022 to display a bar-chart. The line in the chart represents the change in percentage of imports from China from net imports year on year. The axis for this line is on the right side of the chart and it ranges from 4 to 17. Spanning this range across the entire vertical extant of the chart causes small changes in percentages to be amplified. The axis is also cut-off at the horizontal axis. In the absence of net import data in the visualisation it is had to perceive linkage between the change in percentage of Chinese imports relative to net imports in the given time period. 

To modify this visualisation net import data was taken from the provided source and added to the visualisation. This is represented as a grey coloured bar. The red bar (semantically encoded) in the grey bar indicates the portion of Chinese imports. The blue line in the chart represents the percentage of net imports that constitute imports from China. The blue line spans 0-20% and occupies the lower half of the chart giving a clearer picture of reality without amplifying small changes in percentages.

##### Visualisation 2
###### Exports from India to China
|  Original Visualisation |  Modified Visualisation |
|---|---|
| ![Screenshot from 2023-03-14 23-19-47](https://user-images.githubusercontent.com/3922260/226202871-e98bfb50-d2a0-4b11-84af-aa63954af15b.png)  | ![India's Exports to China](https://user-images.githubusercontent.com/3922260/226203077-d4260c23-3036-4698-83d8-b0edcb8c1b83.png)  |
* Click to enlarge above visualisations

The original visualisation uses export data (India to China) in $ billion from 2002 to 2022 to display a bar-chart. The line in the chart represents the change in percentage of exports to China relative to net exports year on year. The axis for this line is on the right side of the chart and it ranges from 3 to 8. Spanning this range across the entire vertical extant of the chart causes small changes in percentages to be amplified. The axis is also cut-off at the horizontal axis. In the absence of net export data in the visualisation it is had to perceive linkage between the change in percentage of exports to China relative to net exports in the given time period. 

To modify this visualisation net export data was taken from the provided source and added to the visualisation. This is represented as a grey coloured bar. The red bar (semantically encoded) in the grey bar indicates the portion of exports to China. The blue line in the chart represents the percentage of net exports that constitute exports to China. The blue line spans 0-10% and occupies the lower half of the chart giving a clearer picture of reality without amplifying small changes in percentages.

##### Visualisation 3
###### Imports from China to nine other countries including India and some of its neighbours 
|  Original Visualisation |  Modified Visualisation |
|---|---|
| ![Screenshot from 2023-03-14 23-21-18](https://user-images.githubusercontent.com/3922260/226202927-e665af9a-9bf2-4e3f-82e7-ffd543c761e2.png)  |  ![China_Radar](https://user-images.githubusercontent.com/3922260/226261581-96954315-ccf2-44c0-8127-c2242c88b4b8.png) |
* Click to enlarge above visualisations

The original visualisation uses data of nine countries - their total imports from China in 2011 and 2021. The data is visualised using a slope chart which highlights the general increase in imports from China. The United States seems to have maintained stability by constraining imports from China to ~18.4% of it's total imports over the 10 year period. This is represented by the nearly straight line parallel to the horizontal axis for USA. This chart could be quite hard to understand for someone who has not seen slope charts before and in the original visualisation the names of 2 countries are missing. 

The visualisation has been modified to represent the Chinese import data of the same countries on a radar plot. This has been complemented with 2 Choropleth maps (2011 and 2021) to  capture the change in percentage of imports from China. Semantic Encoding - A deeper shade of red indicates a higher percentage of imports from China and a lighter shade indicates a lower percentage. Both the Choropleth maps have been colour adjusted so that USA has the same colour in both maps since its percentage remains the same. 

##### Other Visualisations Present in the Story

|  Most Exported Goods |  Most Imported Items | Item-wise Dependency |
|---|---|---|
|  ![Screenshot from 2023-03-14 23-20-31](https://user-images.githubusercontent.com/3922260/226202904-f03c0fa9-6784-48dc-b7d1-af1cd752fcd1.png) |  ![Screenshot from 2023-03-14 23-20-58](https://user-images.githubusercontent.com/3922260/226202920-29535ea6-6e1e-4617-b98d-8d6b37b71224.png) | ![Screenshot from 2023-03-14 23-21-38](https://user-images.githubusercontent.com/3922260/226202938-be737a34-09b8-45ca-8158-b57d265c071e.png) |

The three visualisations above represent and depict the data quite well in line with the narrative presented in the story and were not modified.
