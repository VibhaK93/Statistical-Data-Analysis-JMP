# Statistical-Data-Analysis-JMP
[ProductTestHistory_Raw Data.xlsx](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/files/12786835/ProductTestHistory_Raw.Data.xlsx)

1. **Revenue Distribution**
 - I created a new variable named "Revenue" to calculate the total revenue by multiplying the **number of units sold with the average retail price** for each record. Then, I used JMP's Distribution platform to make a histogram of the Revenue variable along with the related Descriptive Statistics. I removed any clearly extreme outliers and repeated this analysis to observe the results.
 - **Analysis**: The histogram indicates that without excluding outliers in the first case, the distribution will not be normal and the mean will be affected by the outliers. On the other hand, in the second case, after removing two extreme outliers, Revenue 8495.8 and 35559, the distribution will become normal, and the curve will be symmetrical at the center.

[Before Excluding Outliers]![Revenue Distribution_1](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/ff3e7522-8e3d-4ca6-b720-9a73daeafcbf)
[After Excluding Outliers]![Revenue Distribution_2](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/b96a5740-8b32-47eb-bb05-96fa89fccb95)

2. Units sold by region 
- After excluding the extreme outliers identified from the data, Identified the Regions with the highest and lowest average Units Sold per store
- Analysis: The table shows that the Pacific Northwest and southwest regions have highest 343.79 and lowest 179.63 average units sold per store respectively. 
  ![Unitssoldbyregion 1](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/a45ceeba-ee8c-49f2-a4aa-962d859b3f80)

3. Impact of average retail price on units sold
   - Use JMP’s Fit Y by X platform to create a scatterplot of Units Sold (Y) vs. Average Retail Price (X) showcaing with trendline
   - Analysis: The horizontal trendline in the above scatter plot shows the downward slope as the average retail price increases number of unit sold decreases and we can see the strong relationship between the plotted point which are clustered close together to one another.
  <img width="276" alt="AvgpriceVsUnitssold" src="https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/d2724ac3-6dc1-4612-9ab2-dc695a23c8e5">

4. Graph builder exploration:
   - Analysis: The above chart shows the comparison of revenue over the regions and it’s noticeable that Southwest and Rocky Mountains are the top two regions with max revenue so company can focus these two regions from the sales perspective.
 ![Graphbuilder](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/5b68b1aa-e215-49ae-986a-2e91f264ea25)
   - Analysis: The tree map shows the greatest number of units sold in each area, with the Southwest having the most (8100) and the North Atlantic and Florida having the fewest (307). Company can plan tactics to boost the number of units sold in each region from this visualization.
   - ![Graphbuilder2](https://github.com/VibhaK93/Statistical-Data-Analysis-JMP/assets/146596962/30f1c455-d9d3-4b3e-8763-d3d90f4a8291)
