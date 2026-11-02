# WEEK 12 – AUTOMOBILE DATASET ANALYSIS USING PYTHON
## Data Visualization and Competitive Market Positioning

### 1. Introduction
This project focuses on analyzing and visualizing automobile data using Python. The cleaned dataset generated in Week 11 is used to explore vehicle performance, pricing, fuel efficiency, and manufacturer-level comparisons.

### 2. Objectives
- Load the cleaned automobile dataset.
- Analyze relationships between vehicle features.
- Visualize price and performance patterns.
- Compare automobile manufacturers.
- Study correlations among numerical variables.
- Prepare a competitive market positioning report.

### 3. Tools and Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 4. Dataset Overview
The cleaned automobile dataset contains 205 records and includes manufacturer, fuel type, body style, engine specifications, horsepower, mileage, vehicle weight, and price information. It also contains the engineered features `power_to_weight_ratio` and `combined_mpg`.

### 5. Task-wise Implementation

#### Task 1: Load Cleaned Dataset
Imported the required Python libraries and loaded `automobile_cleaned.csv`. Displayed the first five records, dataset dimensions, column names, and verified the newly created features.

#### Task 2: Horsepower vs Price
Created a scatter plot to analyze the relationship between horsepower and price. Used fuel type to distinguish vehicles through different colours.
<img width="942" height="575" alt="image" src="https://github.com/user-attachments/assets/35a2a1f3-8f8d-4a13-826e-ec7a59ada23b" />

#### Task 3: Engine Size vs City MPG
Created a scatter plot comparing engine size and city mileage. Used fuel type as the colour category to compare gas and diesel vehicles.
<img width="868" height="567" alt="image" src="https://github.com/user-attachments/assets/76c3f615-4bf8-48ec-9343-047a0f22cb90" />

#### Task 4: Price Distribution Across Body Styles
Created a box plot to compare price distributions across different automobile body styles, including sedan, hatchback, wagon, hardtop, and convertible.
<img width="897" height="622" alt="image" src="https://github.com/user-attachments/assets/682072c4-ef6a-40b5-8356-59e0528fed73" />

#### Task 5: Price by Fuel Type and Engine Type
Created a grouped bar chart to compare average automobile prices based on fuel type and engine type.
<img width="897" height="567" alt="image" src="https://github.com/user-attachments/assets/d2980e7c-4ecd-4860-aa9c-10a47f8815b2" />

#### Task 6: Correlation Heatmap
Calculated the correlation matrix for selected numerical columns, including engine-size, horsepower, curb-weight, wheel-base, length, width, height, city-mpg, highway-mpg, combined_mpg, power_to_weight_ratio, and price.
Visualized the relationships using a correlation heatmap.
<img width="827" height="647" alt="image" src="https://github.com/user-attachments/assets/d1aec4de-c509-42d5-88d4-abc1df93c17d" />


#### Task 7: Manufacturer-wise Analysis
Grouped the dataset by manufacturer and calculated average price, average horsepower, and average combined MPG. Created a bar chart to compare average prices across manufacturers.

###op

Manufacturer-wise Average Analysis:
make	price	horsepower	combined_mpg
0	alfa-romero	15498.333333	125.333333	23.500000
1	audi	17859.166667	121.000000	21.500000
2	bmw	26118.750000	138.875000	22.375000
3	chevrolet	6007.000000	62.666667	43.666667
4	dodge	7875.444444	86.333333	31.055556
5	honda	8184.692308	80.230769	32.923077
6	isuzu	8916.500000	77.000000	33.500000
7	jaguar	34600.000000	204.666667	16.333333
8	mazda	10652.882353	85.529412	28.823529
9	mercedes-benz	33647.000000	146.250000	19.750000
10	mercury	16503.000000	175.000000	21.500000
11	mitsubishi	9239.769231	104.076923	28.038462
12	nissan	10415.666667	102.555556	29.972222
13	peugot	15489.090909	99.818182	24.545455
14	plymouth	7963.428571	86.714286	31.142857
15	porsche	31400.500000	210.400000	21.700000
16	renault	9595.000000	NaN	27.000000
17	saab	15223.333333	126.666667	23.833333
18	subaru	8541.250000	86.250000	28.541667
19	toyota	9885.812500	92.781250	30.203125
20	volkswagen	10077.500000	81.083333	31.750000
21	volvo	18063.181818	128.000000	23.500000

#### Task 8: Bubble Chart
Created a bubble chart comparing horsepower and combined MPG.

- X-axis: Horsepower
- Y-axis: Combined MPG
- Bubble size: Curb Weight
- Bubble colour: Fuel Type

  

This visualization helps compare vehicle performance and fuel efficiency.

###Plot average price

<img width="912" height="496" alt="image" src="https://github.com/user-attachments/assets/3ff5912a-7076-4465-9fe3-f99a6c085f8c" />

###Bubble Chart

<img width="913" height="482" alt="image" src="https://github.com/user-attachments/assets/273ca3dd-e53d-4fef-bdea-487f389b6353" />


#### Task 9: Competitive Market Positioning Report
Prepared a market positioning report covering:
- Introduction
- Dataset overview
- Key findings
- Performance analysis
- Pricing and brand comparison
- Market opportunities
- Recommendations
- Conclusion

### 6. Results
- Loaded the cleaned automobile dataset.
- Visualized horsepower, price, engine size, and mileage relationships.
- Compared price distributions across body styles.
- Analyzed fuel type and engine type combinations.
- Created a correlation heatmap.
- Compared average price, horsepower, and combined MPG across manufacturers.
- Visualized performance and vehicle weight using a bubble chart.

### 7. Conclusion
Week 12 successfully demonstrated automobile data visualization and market analysis using Python. Different charts and statistical techniques were used to explore vehicle pricing, performance, fuel efficiency, and manufacturer comparisons. The analysis provides a foundation for understanding automobile market trends and supporting data-driven decisions.
