# Statistical-Data-Analysis-JMP
[ProductTestHistory_Raw Data.xlsx](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/files/12786835/ProductTestHistory_Raw.Data.xlsx)

1. **Revenue Distribution**
 - I created a new variable "Revenue" to calculate the total revenue by multiplying the **number of units sold with the average retail price** for each record. Then, I used JMP's Distribution platform to make a histogram of the Revenue variable along with the related Descriptive Statistics. I removed any clearly extreme outliers and repeated this analysis to observe the results.
 - **Analysis**: The histogram indicates that without excluding outliers in the first case, the distribution will not be normal and the mean will be sensitive to the outliers. On the other hand, in the second case, after removing two extreme outliers, Revenue 8495.8 and 35559 from the data, the distribution will become normal, and the curve will be symmetrical at the center.

**Before Excluding Outliers** 

![Revenue Distribution_1](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/ff3e7522-8e3d-4ca6-b720-9a73daeafcbf)

**After Excluding Outliers**

![Revenue Distribution_2](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/b96a5740-8b32-47eb-bb05-96fa89fccb95)

2. Units sold by region 
- After removing extreme outliers from the data, I identified the regions with the highest and lowest average units sold per store.
- Analysis: Based on the results, The Pacific Northwest region has the highest average units sold per store which is 343.79, while the Southwest region has the lowest average units sold per store which is 179.63.
  ![Unitssoldbyregion 1](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/a45ceeba-ee8c-49f2-a4aa-962d859b3f80)

3. Impact of average retail price on units sold
- Used JMP's Fit Y by X platform to create a scatterplot of Units Sold (Y) vs. Average Retail Price (X) showcasing a trendline.
- Analysis: In the scatter plot, the horizontal trendline indicates a negative correlation between the average retail price and the number of units sold. As the price increases, the sales volume decreases. The closely clustered data points on the plot further highlight this strong relationship.
  <img width="276" alt="AvgpriceVsUnitssold" src="https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/d2724ac3-6dc1-4612-9ab2-dc695a23c8e5">

4. Graph builder exploration:
- Analysis: The chart below compares revenue across regions. Southwest and Rocky Mountains have the highest revenue, so the company should focus on these regions for sales.
 ![Graphbuilder](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/5b68b1aa-e215-49ae-986a-2e91f264ea25)
- Analysis: The tree map displays the highest number of units sold in each region, with the Southwest region having the highest number of units sold (8100), while the North Atlantic and Florida regions having the lowest number of units sold (307). This visualization is helpful in planning tactics to increase the number of units sold in each region.
 ![Graphbuilder2](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/30f1c455-d9d3-4b3e-8763-d3d90f4a8291)
