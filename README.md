# Appartment for a MiNI student 

## Project description
This project analyzes the housing market in Warsaw from the perspective of students and graduates of the Faculty of Mathematics and Information Science. The goal is to identify the most cost-effective apartment characteristics and estimate the time required to purchase a property under realistic financial assumptions.

The analysis combines data-driven methods with practical considerations relevant to young professionals entering the real estate market.

## Objectives
- Identify the optimal apartment size in terms of price per square meter  
- Analyze the relationship between the number of rooms and unit price  
- Determine an optimal location balancing cost and commuting distance  
- Estimate the time required to afford a property under different saving strategies  

## Key findings

### Apartment size
The lowest price per square meter is observed for apartments in the range: **50–70 m²**.  
This range was selected for further analysis.

### Number of rooms
Three-room apartments offer the most favorable price per square meter.

### Location
- The highest prices are concentrated in central districts and Mokotów  
- An optimal balance between cost and accessibility is achieved at a distance of **5–7.5 km** from the city center  

## Financial analysis

**Assumptions:**
- Estimated cost per person: approximately **400,000 PLN** (purchase in a pair)  
- Annual salary growth: **5%**  
- Savings invested with a return of **4–5%**  

**Results:**

| Savings rate | Estimated age of purchase |
|--------------|---------------------------|
| 10%          | 45–50 years              |
| 15%          | ~37 years                |
| 20%          | ~32 years                |

The analysis shows that the savings rate has a significant impact on the time required to purchase a property.

## Technologies
- R  
- ggplot2  
- dplyr  
- RStudio  

## How to run
1. Open the `.Rproj` file in RStudio  
2. Install required packages:
   ```r
   install.packages(c("ggplot2", "dplyr"))
   ```
3. Run the scripts to reproduce the analysis and visualizations  

## Authors
- Wiktoria Grodzka  
- Maria Harbaty  
- Michał Grzegory  

## Context
This project was developed as part of university coursework and demonstrates the application of data analysis to real-world economic decision-making.
