# Ecommerce

### Dashboard Link : https://github.com/Ashwin02013/Power-BI/blob/main/TataCliq/TataCliq.pbix

## Problem Statement

This dashboard helps the Ecommerce Admins understand their customers better. It helps the ecommerce Admins know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the delay & delivery time, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted delays.

Since, number of neutral/dissatisfied customers (almost 57 %) are more than satisfied customers (around 43 %), thus in all they must work on improving their services. 

Also since average delay in dispatching & delivery both is 1 - 5 days, thus they must try to reduce it.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a Excel file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

- Step 4 : It was observed that in none of the columns errors.

- Step 5 : Visual filters (Slicers) were added for five fields named "Year", "Month", "Category", "Location" & "Ratings".
This is the homepage with no selections

![Screenshot 2024-08-12 125924](https://github.com/user-attachments/assets/12e71131-b5e7-453c-97b2-8edfaab2155d)

- Step 6 : Five card visuals were added to the canvas, Representing Total Revenue , Total Profit , Total Order,Average Ratings & Total Products as shown in the above picture.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           Although, by default, while calculating average, blank values are ignored.

- Step 7 : A Line chart was added to the report design area representing the Total Revenue for years and the trend line and forecast was active to predict the future revenue as follows.
The line chart was drilled down to quarters ( Q1 - Q4 )

![Screenshot 2024-08-12 130018](https://github.com/user-attachments/assets/3d79da1e-5803-479e-98b5-d730198e415b)

Line chart drilled down to months ( JAN – DEC )

![Screenshot 2024-08-12 130126](https://github.com/user-attachments/assets/699e0e7d-35ef-441a-ac47-bb75a53aa247)

Line chart drilled down by weektype ( WEEKDAY , WEEKEND )

![Screenshot 2024-08-12 130223](https://github.com/user-attachments/assets/74eb6027-86cf-4f3b-9edb-124f7cf51d3a)

- Step 8 : A Stacked bar Chart was also added to the report design area representing the Top N number of product used by sub cateogory and the corresponding revenue of it.

  ![Screenshot 2024-08-12 130300](https://github.com/user-attachments/assets/063ddfce-4f29-4888-ab6b-2cd37879c120)

- Step 9 : A map was also added to the report design area representing the location where the products were delivered.  

   ![Screenshot 2024-08-07 165457](https://github.com/user-attachments/assets/23061f83-0ea3-41d0-8840-44398842363e)

   The above map style was changed from light to aerial to match the dark theme and the locations can also be zoomed by clicking the plus icon and it is shown in the image as follows.

- The following image is zoomed only by once
 
  ![Screenshot 2024-08-07 165744](https://github.com/user-attachments/assets/ac2511cb-e648-47a6-9d36-b9b773ce961a)
   
- The following image is zoomed in again by once

  ![Screenshot 2024-08-07 170153](https://github.com/user-attachments/assets/8beba681-7c12-4028-8c8f-d15269da51cf)

- This could be zoomed in to street of a city 

   ![Screenshot 2024-08-07 170306](https://github.com/user-attachments/assets/75321e59-7302-40d3-9b86-cd92c2460962)

- Step 10 : A Rectangle was inserted to replicate the functionality of a task bar and buttons ( Blanks ) were added and images were inserted from " icon-8 " which contained four blanks representing " 1 - logo " followerd by a slicer with search which replicates the search tab ,Then " 2 - Expand "," 3 - Favourite ", " 4 - Cart ".

  ![Screenshot 2024-08-12 130407](https://github.com/user-attachments/assets/f47d2315-f247-48a7-b155-2b5fbdd9516b)

- Step 11 : More tab , Favourite tab , Cart tab were created in correspondence with above mentioned tab names.

  ![Screenshot 2024-08-08 091335](https://github.com/user-attachments/assets/74895604-cbca-42cd-a08b-4c342159407f)

-  " 1 - logo " tata cliq logo was downloaded as png and was filled 0 transparency to make atmost visible,"
-  " Search " A slicer is added to replicate the search 
-  " 2 - Expand " Expand symbol was added to show more options for the selected products, A slicer was added with search option to replicate the activities of the search bar . In the following image one can notice the data in visuals display the value corresponding to the search synced from " Home " page and the search bar in the " More " page also has the same values.
- The following image is the more tab with the search tab actively selected for a particular product that is "Samsung Mobile"

    ![Screenshot 2024-08-12 130526](https://github.com/user-attachments/assets/14f8851c-7b64-4a25-bab4-29848f28f8cc)

- Before selecting a product , When the keyword for the product is selected it provides category under which the product comes as shown in image below.

    ![Screenshot 2024-08-12 130653](https://github.com/user-attachments/assets/a35e9880-1334-40ad-8c22-52637fe15e4f)

- As shown in the above picture the " Samsung " keyword searched comes under the  " Phones and Tablet " category and when the down arrow is clicked it display the subcategory that has the product samsung as follows

   ![Screenshot 2024-08-12 130750](https://github.com/user-attachments/assets/6daac5c2-7a01-40f9-bbbe-e5f813d1a8a2)

- On repeating the same process , It display the variety of mobiles which has the keyword " Samsung " as follows

  ![Screenshot 2024-08-12 130827](https://github.com/user-attachments/assets/876eee4b-29b8-4f6f-90e1-bbf9546ce4bc)

- As shown in the above image there are two products which has the " Samsung " keyword in it and the background visuals display the same data of all the products combined . When the product is selected by clicking the checkbox the visuals in the background will display the values of the particular product selected , That is " Samsung Galaxy A02 - 64B HDD - 3RB RAM Smartphone " as follows.

  ![Screenshot 2024-08-12 130858](https://github.com/user-attachments/assets/0cdfacbb-a2ed-46c1-adb7-4474d4b8334d)

- " 3 - favourite " favourite icon  was added which navigate to a tab containing a screenshot of the actual favourite tab of "tatacliq" website to replicate the theme of it.

    ![Screenshot 2024-08-12 130952](https://github.com/user-attachments/assets/635777e5-3d1a-488d-8fbb-91f2f7701cb6)

- " 4 - Cart " Cart icon  was added which navigate to a tab containing a screenshot of the actual Cart of " tatacliq " website to match the theme of it .

    ![Screenshot 2024-08-12 132113](https://github.com/user-attachments/assets/5d77e898-c9b6-4752-9ec0-8e9786c314fe)

- Step 12 : More tab was inserted with four slicers representing year , month , location & rating . The following image is the screenshot of the tab with zero filters selected.

    ![Screenshot 2024-08-12 132207](https://github.com/user-attachments/assets/f651a380-4b60-4c50-b33c-852dfdec82e0)

- The following image is the more tab with all filters that is slicer active (" Year " is set to 2020 , " Location " is set to North East, " Month " is set to May , " Rating " is set to All)

  ![Screenshot 2024-08-12 132306](https://github.com/user-attachments/assets/0af99d45-00da-42bd-9bfe-a7934785d864)

- Step 13 : In More tab a donut chart was added which represents the revenue earned from subcategories.

  ![Screenshot 2024-08-08 091522](https://github.com/user-attachments/assets/abc5bf4e-5403-4001-b3a8-8bb9601665d1)

- Step 14 : Line and Clustered column chart was also added to represent the revenue earned which is represented by the orange ccolumns from subcategories with respect to the total cost required to produce the product which is represented with the blue line.

  ![Screenshot 2024-08-07 165018](https://github.com/user-attachments/assets/19e62f1f-58bd-4357-b8b2-fdcfea0b46a1)

- Step 15 : A gauge was also to provide the number of order delivered successfully that is not returned due to any reason with the starting range as 0 and end range as number of products totaly delivered.

  ![Screenshot 2024-08-08 091603](https://github.com/user-attachments/assets/a1fcc5b2-ae2d-4dfc-9439-9694861e5028)

- Step 16 : A " Q & A " chart was also added to act as interactive bot which gets the data the admin needs by getting the query as the keywords.The following image represents the Q & A tab when it is inactive 

  ![Screenshot 2024-08-08 091638](https://github.com/user-attachments/assets/5b51781b-6999-41a3-98c5-d4a5ba2971c9)

- The following image represents the Q & A tab when it is actively displaying values
  
  ![Screenshot 2024-08-12 132957](https://github.com/user-attachments/assets/d5dcd096-313c-4592-a19c-63deb6cd4df0)

  One can check for it correctness by cross checking with the selections of the slicer and data displayed in the visuals.

- Step 17 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Package handling

  (b) Services
  
  (c) Quality of product
  
  (d) Ease of online payment
  
  (e) Dispatching & delivery time 
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

