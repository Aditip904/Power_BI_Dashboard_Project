# Customers_Dashboard
![Screenshot 2024-03-20 233744](https://github.com/Aditip904/Power_BI_Dashboard_Project/assets/112500658/73123fa5-f46d-4e16-bf45-d2e48374c96b)


# Problem Statement
The Global Supermarket Analysis Dashboard is a tool of the reflection and ideology that give early notions about the industry, which looks at global supermarket chains. It depicts the main underlying statistical figures like the sales turnover, profits, number of customers coming in, and the damage in products using diverse presentations including line charts and bar graphs. Clients now have the flexibility of seeing the market supply and demand analysis; figure out how the demand and expansion are fast and trade on them. The panel boasts for data comparison with peers and industry standards, facilitating the process of defining efficient procedures and the right approach. It is a unifying system of a quantitative metric composed with a detailed social media sentiment and customer experience assessment. Consequently, you get a well-rounded view of the market dynamics. For the most part, the tool is useful for the executives, the marketers and analysts who obtain the necessary information when they make decision along with the competition among those stores in the market.

# Steps to be followed 

Step 1: Load data into Power BI Desktop, dataset is a csv file.
![Screenshot 2024-03-21 000150](https://github.com/Aditip904/Power_BI_Dashboard_Project/assets/112500658/b920d7c0-c798-421a-9390-f46174f16c07)

Step 2: Open power query editor & in view tab under Data preview section, check "column Sales", "column Quantity", "column Return"  & "column Delivery" options for Cards.
![Screenshot 2024-03-21 000325](https://github.com/Aditip904/Power_BI_Dashboard_Project/assets/112500658/24239bf4-9923-409b-98f1-943862818308)

Step 3: Also since by default, profile will be opened only for 48700 rows so you need to select "column profiling based on entire dataset".

Step 4: It was observed that there are in the table "Return" as it's Headers to done as first Row from Transform data & all other data are cleaned .

Step 5: For calculating average Delivery Days we will create a column as no of days are taken to deliver by using the formula from transform table.

Step 6: In the report view, under the view tab, theme was selected.

Step 7: Since the data contains various ratings, thus in order to represent sales, a new visual was added using the maps in the visualizations pane in report view.

Step 8: Visual filters (Slicers) were added for four fields named "2012", "2013", "2014" & "2015".

Step 9: Two card visuals were added to the canvas, one representing sum of profit in thousands & other representing the loss in the products. Using Bar Chart filter from the visuals. Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
![Screenshot 2024-03-21 000325](https://github.com/Aditip904/Power_BI_Dashboard_Project/assets/112500658/24239bf4-9923-409b-98f1-943862818308)
 
Step 10. A bar chart was also added to the report design area representing the number of Top Customers . While creating this visual, field named "Gender" was also added to the Legends bucket.
![Screenshot 2024-03-21 000405](https://github.com/Aditip904/Power_BI_Dashboard_Project/assets/112500658/61c0c2f0-5b08-4257-ae00-1454dc9037bf)

• Step 11: Ratings Visual was used to represent different ratings mentioned below.

(a) Baggage Handling

(b) Check-in Services

(c) Cleanliness


The final look of the Dashboard is as follows
![Screenshot 2024-03-20 233744](https://github.com/Aditip904/Power_BI_Dashboard_Project/assets/112500658/73123fa5-f46d-4e16-bf45-d2e48374c96b)
