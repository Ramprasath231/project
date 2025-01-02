
# Project Title


# Cricket Team's Yearwise Analaysis



## Problem Statement

This dashboard helps how the most popular Cricket teams like India,Australia, Newzealand, SouthAfrica,England,Srilanka,pakistan and westindies are performing their international matches(ODI,T20 and test) From 2000 to 2024.


We also see winning % and Losing % from this dashboard.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 9 : Four card visuals were added to the canvas,  one is home page which use to see a history of Cricket Team's and Other Three are ODI,T20 and Test Performance from 2000 to 2024.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : A bar chart was also added to the report design area representing team performance winning % and Losing %.
- Step 11 : Ratings Visual was used to represent Team's international matches  ratings mentioned below,

  (a) India

  (b) Australia

  (C) Newzealand

  (d) SouthAfrica

  (e) England

  (f) Srilanka

  (g) pakistan

  (h) westindies

In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some teams are played for those years.


- Step 12 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option cricket logo was added to the report design area. 

- Step 13 : Calculated column was created in which, Cricket Team's  were grouped into ODI ,T20 and Test.

        
Snap of new calculated column ,

![Snap_1]![India](https://github.com/user-attachments/assets/0af96642-31f7-4366-9a20-c8ac9aa8ee58)


![Snap_2]
![Australia](https://github.com/user-attachments/assets/6ea9db5b-fe2e-41dc-8095-c8091d9d0e41)

![Snap_3]![Nz](https://github.com/user-attachments/assets/f670ed1c-20e3-4a10-a59b-005ad8875686)

![Snap_4]!![SA](https://github.com/user-attachments/assets/53b92461-7a20-42ca-a2fa-62b0cd75672d)


![Snap_5]![eng](https://github.com/user-attachments/assets/6d1eb053-6bf5-450c-9d9f-a13c810ef37b)


![Snap_6]![Srilanka](https://github.com/user-attachments/assets/2e3a1228-2a61-4c67-8137-70f61af6b615)


        
 ![Snap_7]![pakistan](https://github.com/user-attachments/assets/ed1a7baa-c714-4f03-8c58-be0a74364eae)


 
  ![Snap_8]![Wi](https://github.com/user-attachments/assets/4460c98d-0e3a-449d-8892-2439b83f54d3)

 
 - Step 14 : The report was then published to Power BI Service.
 
 
![Publish_Message]![Screenshot 2025-01-02 084237](https://github.com/user-attachments/assets/e0362fb1-6cb6-449e-b31a-3a00289eff91)
