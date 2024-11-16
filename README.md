# Recreating Nicholas's Ladder Target Visual in Power BI  

Hi everyone,  

In this repository, I’ll explain how I recreated the chart originally created by Nicholas.
[Here’s the link to Nicholas's chart.](https://www.linkedin.com/posts/nicholas-lea-trengrouse_powerbi-analytics-datavizualisation-activity-7262373673330688002-st9_?utm_source=share&utm_medium=member_desktop)

This is my version of the chart,
![Chart](https://github.com/user-attachments/assets/8c2719f3-e4df-44b3-befe-eb93ee9314db)


## Step-by-Step Process  

1. **Creating a Disconnected Table**  
   - I started by creating a disconnected table to represent percentage bins in steps of 10%.
  
     
     ![image](https://github.com/user-attachments/assets/d3452d68-bfff-4a96-9478-1c84975d06d9)


     
2. **Mapping Data to Bins**  
   - When dropping the bins along with the Sales Target Achieved %, the results were plotted across all the bins.      
   - This allowed me to use an `IF` function to assign specific colors to the bars based on the desired conditions.
  
   ![image](https://github.com/user-attachments/assets/c57ee8e9-5284-4f3d-91cb-35f8530d5112) ![image](https://github.com/user-attachments/assets/3db137d3-d996-4edc-a651-349de88f6e0f)




5. **Using a Stacked Bar Chart**  
   - Finally, I used a stacked bar chart to visualize the data, aligning it with the ladder target visual concept.
  
   ![image](https://github.com/user-attachments/assets/0db278ff-b00b-4893-af6a-d9820414e983)

- This is the approach I took to build this chart; the rest was done through design formatting.
- Feel free to explore the code and report files in this repository to see how I achieved this step-by-step!

  Thank you!
[Fawzan](https://www.linkedin.com/in/fawzanameer/)
