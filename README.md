# Tableau
Some of the Tableau dashboards I made and some notes from my Tableau experience.</br>

1. The most basic things are dimensions and measures in Tableau. Dimensions are categorical values and measures are quantifiable values.</br>
2. Tooltip is the thing which pops up when you drag the cursor on any point, it's like a pop-up window. Of-course you can edit the tooltip, it gives you the ability to show the info that you want the people to see</br> 

3. Somethimes we convert dimensions into measures for visualization because if visualize dimension directly we get AGG. version, therefore to aviod that, we convert dimension into the measure.</br>

4. Sanky chart tutorial- https://www.youtube.com/watch?v=GNHpEm63hT8</br>

5. To make a particular thing stand out in different colour we have to use a calculated field.</br>
   for e.g.
<img width="613" alt="Screenshot 2025-01-07 at 11 26 18 PM" src="https://github.com/user-attachments/assets/8f3f92b0-0620-4a68-ad03-1527b780e29d" /> </br>

Over here I was able to differentiate above average and below average by putting Avg. line in the chart and then creating a calculated field. ( sum([Sales])>=window_avg(sum([Sales])). LAstly putting the calculated field in colour.

<img width="735" alt="Screenshot 2025-01-09 at 7 56 16 PM" src="https://github.com/user-attachments/assets/a243b79f-7265-4287-981b-0c154b599165" />


6. **When you are publishing a workbook on Tableau with a data source that has been used before and you have published one workbook previously then remember to uncheck the box which asks to replace the previous workbook with the new one, otherwise your previous workbook will get replaced keeping the same name as before but you won't be able to see the previous workbook** </br>

7. Joins combine data at the database level, whereas data blending happens at the visualization layer in Tableau.

8. A highlight table in Tableau uses the Square mark type to represent data values visually. Each square is colour-coded based on the measure values to highlight differences and trends within the data.

9. For a stacked bar chart to appear the only thing you need is **one measure** and a line chart to appear is **a measure followed by date**.

10. Any thing which is a discrete whether it is a measure or a dimension will be in **blue colour**

 
<img width="848" alt="Screenshot 2025-01-30 at 1 18 49 PM" src="https://github.com/user-attachments/assets/50cb1909-b137-48ce-a831-79761f5085ca" />

11. Treemaps are the type of charts that cannot be resized using a marks card

12. Migrated Data means the workbook was created in the **previous version of the Tableau desktop**

13. **An Axis, A field label and a header can sort a visualization**

<img width="595" alt="Screenshot 2025-02-03 at 12 31 30 PM" src="https://github.com/user-attachments/assets/ec79644d-a11a-4cab-9519-517f44fbb76a" />


