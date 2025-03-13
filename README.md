# Diamond Price & Quality Analysis Dashboard (Interactive Dashboard using Power BI)

This Power BI dashboard provides an interactive analysis of diamond pricing and quality factors such as cut, color, clarity, and carat weight. It helps jewelers, retailers, and customers understand how these factors influence price trends and make data-driven purchasing decisions.

## Project Objective
The objective of this project is to analyze diamond price variations based on different quality factors such as cut, color, clarity, carat, and dimensions. The interactive Power BI dashboard enables jewelers, retailers, and customers to make informed decisions about diamond purchases by understanding price trends and influential factors.

## Dataset Used
The dataset contains 53,940 records with key attributes such as:
- *Carat* (Weight of the diamond)
- *Cut* (Quality of the cut: Ideal, Premium, Good, etc.)
- *Color* (Diamond color grades: D to J)
- *Clarity* (Diamond clarity levels: IF, VVS1, VVS2, etc.)
- *Depth* (Depth percentage of the diamond)
- *Table* (Width of the top facet)
- *Price* (Price in US dollars)
- *x, y, z* (Dimensional measurements in mm)
- <a href = "">Dataset</a>

## Key Questions (KPIs) Analyzed
### Price & Count Analysis
1. What is the *total count* of diamonds available by each cut type? (KPI Card / Table)
2. What is the *minimum, maximum, and average price* of diamonds in each clarity category? (Bar Chart / KPI Cards)
3. How does the *price distribution* vary across different *cut and color* combinations? (Stacked Column Chart)
4. What is the *average price of diamonds with a carat weight greater than 1.5?* (Slicer-Based Analysis / KPI)

### Comparative Analysis
5. How does the *average price per carat* vary for each *cut quality? *(Line Chart / Scatter Plot)
6. Which *clarity grade has the highest average price per carat?* (Table / Heatmap)
7. How does the *distribution of diamond prices compare across different depth percentages?* (Box Plot)
8. What is the *price trend among diamonds with similar table sizes but different clarity levels?* (Line Chart)

### Price & Carat Trends
9. How does *carat weight affect price across different cuts?* (Scatter Plot / Trend Line)
10. What is the *price variation for diamonds between 0.5 to 1.0 carat compared to 1.5 to 2.0 carat?* (Histogram / Distribution Chart)
11. Which *carat weight range contributes the most to total revenue?* (Pie Chart / KPI Cards)
12. What is the *percentage of diamonds priced above $5000 and their distribution by cut?* (Pie Chart / Filtered Bar Chart)

### Dimensional & Quality Impact
13. What is the *relationship between diamond dimensions (x, y, z) and price?* (3D Scatter Plot)
14. How does the *table size influence diamond pricing trends?* (Line Chart)
15. Which *depth percentage range corresponds to the highest average price?* (Box Plot / KPI Card)
16. What is the *most expensive diamond in the dataset in terms of price per carat?* (Filtered Table View)

### Market & Customer Insights
17. Which *combination of color, clarity, and cut has the highest total revenue contribution?* (Treemap)
18. Which *diamond cut has the highest price variation?* (Standard Deviation KPI / Box Plot)
19. What is the *price trend of diamonds with the same cut but different clarity levels?* (Stacked Line Chart)
20. What is the *relationship between clarity and customer preference (most frequently occurring clarity grade)?* (Bar Chart)

## Process
- Cleaned and prepared the data by removing anomalies and ensuring consistency.
- Created pivot tables and statistical summaries to extract key insights.
- Designed an interactive Power BI dashboard with filters, slicers, and visualizations.
- Integrated charts like bar graphs, scatter plots, and heatmaps to represent trends effectively.

## Dashboard Screenshot
<a href = "">Dashboard</a>

## Project Insights
- *Cut Quality Impact:* Ideal and Premium cut diamonds have significantly higher prices due to their superior light reflection properties.
- *Color & Clarity Influence:* Diamonds with color grades D-F and clarity grades IF-VVS1 fetch the highest prices, indicating a strong preference for higher purity stones.
- *Carat Price Trend:* Price increases exponentially with carat weight, especially beyond the 1-carat mark.
- *Dimensional Impact:* Depth and table size significantly affect diamond brilliance, with diamonds having a depth percentage between 60-62% and table size around 55-58% achieving the highest valuations.
- *Market Trends:* Diamonds priced above $5000 are predominantly Ideal and Premium cut, with a majority falling in the 1.5-2.5 carat range.

## Final Conclusion
For optimal pricing and valuation of diamonds, retailers and customers should prioritize diamonds with *superior cut quality, higher clarity, and optimal carat weight. The insights from this dashboard highlight that **Ideal and Premium cuts provide the best balance of quality and price appreciation. Additionally, customers looking for a balance between affordability and quality may opt for **VS1-VS2 clarity diamonds* in the *G-H color range*, as they offer a near-flawless look at a more competitive price. These findings can help jewelers refine pricing strategies, improve inventory management, and target customer preferences effectively.
