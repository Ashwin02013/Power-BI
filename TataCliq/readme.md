#Ecommerce

### Dashboard Link : https://github.com/Ashwin02013/Power-BI/blob/main/TataCliq/TataCliq.pbix
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

![image](https://github.com/user-attachments/assets/1c03a00d-08da-4c91-ae6b-53fac14d05e2)

Line chart drilled down to months ( JAN – DEC )

![image](https://github.com/user-attachments/assets/aced182d-6938-4c70-ad92-d73c23935f3f)

Line chart drilled down by weektype ( WEEKDAY , WEEKEND )

![image](https://github.com/user-attachments/assets/43bce807-b12c-45b7-9bf1-561fce88a7d1)

- Step 8 : A Stacked bar Chart was also added to the report design area representing the Top N number of product used by sub cateogory and the corresponding revenue of it.

  ![image](https://github.com/user-attachments/assets/d4a0566b-bed7-4156-9cb8-d90a2e90866d)

- Step 9 : A map was also added to the report design area representing the location where the products were delivered.  

   ![Screenshot 2024-08-07 165457](https://github.com/user-attachments/assets/7c45209d-89f4-43e7-ab3a-100e0762c048)

   The above map style was changed from light to aerial to match the dark theme and the locations can also be zoomed by clicking the plus icon and it is shown in the image as follows.

- The following image is zoomed only by once
 
  ![Screenshot 2024-08-07 165744](https://github.com/user-attachments/assets/918127cb-a562-44d4-a052-b1579845d7f3)
   
- The following image is zoomed in again by once

  ![Screenshot 2024-08-07 170153](https://github.com/user-attachments/assets/96a7d828-a781-40c1-9491-47317bb72171)

- This could be zoomed in to street of a city 

   ![Screenshot 2024-08-07 170306](https://github.com/user-attachments/assets/126c5b46-3f50-432f-b016-c0ee93b0ff6a)

- Step 10 : A Rectangle was inserted to replicate the functionality of a task bar and buttons ( Blanks ) were added and images were inserted from " icon-8 " which contained four blanks representing " 1 - logo " followerd by a slicer with search which replicates the search tab ,Then " 2 - Expand "," 3 - Favourite ", " 4 - Cart ".

  ![image](https://github.com/user-attachments/assets/f8aaa204-6d15-4e16-b3a5-74aa0994bc5f)

- Step 11 : More tab , Favourite tab , Cart tab were created in correspondence with above mentioned tab names.

  ![Screenshot 2024-08-08 091335](https://github.com/user-attachments/assets/6943f9c2-35b9-4719-a033-25713aa5c035)

-  " 1 - logo " tata cliq logo was downloaded as png and was filled 0 transparency to make atmost visible,"
-  " Search " A slicer is added to replicate the search 
-  " 2 - Expand " Expand symbol was added to show more options for the selected products, A slicer was added with search option to replicate the activities of the search bar . In the following image one can notice the data in visuals display the value corresponding to the search synced from " Home " page and the search bar in the " More " page also has the same values.
- The following image is the more tab with the search tab actively selected for a particular product that is "Samsung Mobile"

    ![image](https://github.com/user-attachments/assets/7a30acd9-2dc6-478f-ad0f-4fcabbb23474)

- Before selecting a product , When the keyword for the product is selected it provides category under which the product comes as shown in image below.

    ![image](https://github.com/user-attachments/assets/455888a1-ae3c-43dc-8247-81be3723e1b6)

- As shown in the above picture the " Samsung " keyword searched comes under the  " Phones and Tablet " category and when the down arrow is clicked it display the subcategory that has the product samsung as follows

   ![image](https://github.com/user-attachments/assets/91ed3e59-a3b0-46fc-b6ec-ce76d1a3e7f0)

- On repeating the same process , It display the variety of mobiles which has the keyword " Samsung " as follows

  ![image](https://github.com/user-attachments/assets/723becf8-b89d-4d78-b494-3e1f5c60dd81)

- As shown in the above image there are two products which has the " Samsung " keyword in it and the background visuals display the same data of all the products combined . When the product is selected by clicking the checkbox the visuals in the background will display the values of the particular product selected , That is " Samsung Galaxy A02 - 64B HDD - 3RB RAM Smartphone " as follows.

  ![image](https://github.com/user-attachments/assets/bdac35f8-047c-4510-889f-c30b36263f5f)

- " 3 - favourite " favourite icon  was added which navigate to a tab containing a screenshot of the actual favourite tab of "tatacliq" website to replicate the theme of it.

    ![image](https://github.com/user-attachments/assets/531d035c-f064-41ad-9272-33b115cfbec6)

- " 4 - Cart " Cart icon  was added which navigate to a tab containing a screenshot of the actual Cart of " tatacliq " website to match the theme of it .

    ![image](https://github.com/user-attachments/assets/d2dcf568-929a-49a1-a24f-dfd08dc5adbb)

- Step 12 : More tab was inserted with four slicers representing year , month , location & rating . The following image is the screenshot of the tab with zero filters selected.

    ![image](https://github.com/user-attachments/assets/164fb61b-61bc-4129-a5b0-84e1f3f65b58)

- The following image is the more tab with all filters that is slicer active (" Year " is set to 2020 , " Location " is set to North East, " Month " is set to May , " Rating " is set to All)

  ![image](https://github.com/user-attachments/assets/a763100e-8f6f-452c-a0fd-49688ad5bc13)

- Step 13 : In More tab a donut chart was added which represents the revenue earned from subcategories.

  ![Screenshot 2024-08-08 091522](https://github.com/user-attachments/assets/058a7b71-f0ff-4bb9-9c56-6caef9e14e7b)

- Step 14 : Line and Clustered column chart was also added to represent the revenue earned which is represented by the orange ccolumns from subcategories with respect to the total cost required to produce the product which is represented with the blue line.

  ![Screenshot 2024-08-07 165018](https://github.com/user-attachments/assets/4f3631f0-2838-4daa-8222-649bd0e229c2)

- Step 15 : A gauge was also to provide the number of order delivered successfully that is not returned due to any reason with the starting range as 0 and end range as number of products totaly delivered.

  ![Screenshot 2024-08-08 091603](https://github.com/user-attachments/assets/1acfd473-9a2c-46f5-8495-243de727ce51)

- Step 16 : A " Q & A " chart was also added to act as interactive bot which gets the data the admin needs by getting the query as the keywords.The following image represents the Q & A tab when it is inactive 

  ![Screenshot 2024-08-08 091638](https://github.com/user-attachments/assets/262e3643-1478-4610-8f6b-be42f142c7c5)

- The following image represents the Q & A tab when it is actively displaying values
  
  ![image](https://github.com/user-attachments/assets/96d4b99a-c1d1-49ff-8408-c38252a75878)

  One can check for it correctness by cross checking with the selections of the slicer and data displayed in the visuals.

- Step 17 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Package handling

  (b) Services
  
  (c) Quality of product
  
  (d) Ease of online payment
  
  (e) Dispatching & delivery time 
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.


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

![image](https://github.com/user-attachments/assets/7bd9e87f-074a-495b-880a-4665e3519875)

- Step 6 : Five card visuals were added to the canvas, Representing Total Revenue , Total Profit , Total Order,Average Ratings & Total Products as shown in the above picture.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           Although, by default, while calculating average, blank values are ignored.

- Step 7 : A Line chart was added to the report design area representing the Total Revenue for years and the trend line and forecast was active to predict the future revenue as follows.
The line chart was drilled down to quarters ( Q1 - Q4 )

![image](https://github.com/user-attachments/assets/1c03a00d-08da-4c91-ae6b-53fac14d05e2)

Line chart drilled down to months ( JAN – DEC )

![image](https://github.com/user-attachments/assets/aced182d-6938-4c70-ad92-d73c23935f3f)

Line chart drilled down by weektype ( WEEKDAY , WEEKEND )

![image](https://github.com/user-attachments/assets/43bce807-b12c-45b7-9bf1-561fce88a7d1)

- Step 8 : A Stacked bar Chart was also added to the report design area representing the Top N number of product used by sub cateogory and the corresponding revenue of it.

  ![image](https://github.com/user-attachments/assets/d4a0566b-bed7-4156-9cb8-d90a2e90866d)

- Step 9 : A map was also added to the report design area representing the location where the products were delivered.  

   ![Screenshot 2024-08-07 165457](https://github.com/user-attachments/assets/7c45209d-89f4-43e7-ab3a-100e0762c048)

   The above map style was changed from light to aerial to match the dark theme and the locations can also be zoomed by clicking the plus icon and it is shown in the image as follows.

- The following image is zoomed only by once
 
  ![Screenshot 2024-08-07 165744](https://github.com/user-attachments/assets/918127cb-a562-44d4-a052-b1579845d7f3)
   
- The following image is zoomed in again by once

  ![Screenshot 2024-08-07 170153](https://github.com/user-attachments/assets/96a7d828-a781-40c1-9491-47317bb72171)

- This could be zoomed in to street of a city 

   ![Screenshot 2024-08-07 170306](https://github.com/user-attachments/assets/126c5b46-3f50-432f-b016-c0ee93b0ff6a)

- Step 10 : A Rectangle was inserted to replicate the functionality of a task bar and buttons ( Blanks ) were added and images were inserted from " icon-8 " which contained four blanks representing " 1 - logo " followerd by a slicer with search which replicates the search tab ,Then " 2 - Expand "," 3 - Favourite ", " 4 - Cart ".

  ![image](https://github.com/user-attachments/assets/f8aaa204-6d15-4e16-b3a5-74aa0994bc5f)

- Step 11 : More tab , Favourite tab , Cart tab were created in correspondence with above mentioned tab names.

  ![Screenshot 2024-08-08 091335](https://github.com/user-attachments/assets/6943f9c2-35b9-4719-a033-25713aa5c035)

-  " 1 - logo " tata cliq logo was downloaded as png and was filled 0 transparency to make atmost visible,"
-  " Search " A slicer is added to replicate the search 
-  " 2 - Expand " Expand symbol was added to show more options for the selected products, A slicer was added with search option to replicate the activities of the search bar . In the following image one can notice the data in visuals display the value corresponding to the search synced from " Home " page and the search bar in the " More " page also has the same values.
- The following image is the more tab with the search tab actively selected for a particular product that is "Samsung Mobile"

    ![image](https://github.com/user-attachments/assets/7a30acd9-2dc6-478f-ad0f-4fcabbb23474)

- Before selecting a product , When the keyword for the product is selected it provides category under which the product comes as shown in image below.

    ![image](https://github.com/user-attachments/assets/455888a1-ae3c-43dc-8247-81be3723e1b6)

- As shown in the above picture the " Samsung " keyword searched comes under the  " Phones and Tablet " category and when the down arrow is clicked it display the subcategory that has the product samsung as follows

   ![image](https://github.com/user-attachments/assets/91ed3e59-a3b0-46fc-b6ec-ce76d1a3e7f0)

- On repeating the same process , It display the variety of mobiles which has the keyword " Samsung " as follows

  ![image](https://github.com/user-attachments/assets/723becf8-b89d-4d78-b494-3e1f5c60dd81)

- As shown in the above image there are two products which has the " Samsung " keyword in it and the background visuals display the same data of all the products combined . When the product is selected by clicking the checkbox the visuals in the background will display the values of the particular product selected , That is " Samsung Galaxy A02 - 64B HDD - 3RB RAM Smartphone " as follows.

  ![image](https://github.com/user-attachments/assets/bdac35f8-047c-4510-889f-c30b36263f5f)

- " 3 - favourite " favourite icon  was added which navigate to a tab containing a screenshot of the actual favourite tab of "tatacliq" website to replicate the theme of it.

    ![image](https://github.com/user-attachments/assets/531d035c-f064-41ad-9272-33b115cfbec6)

- " 4 - Cart " Cart icon  was added which navigate to a tab containing a screenshot of the actual Cart of " tatacliq " website to match the theme of it .

    ![image](https://github.com/user-attachments/assets/d2dcf568-929a-49a1-a24f-dfd08dc5adbb)

- Step 12 : More tab was inserted with four slicers representing year , month , location & rating . The following image is the screenshot of the tab with zero filters selected.

    ![image](https://github.com/user-attachments/assets/164fb61b-61bc-4129-a5b0-84e1f3f65b58)

- The following image is the more tab with all filters that is slicer active (" Year " is set to 2020 , " Location " is set to North East, " Month " is set to May , " Rating " is set to All)

  ![image](https://github.com/user-attachments/assets/a763100e-8f6f-452c-a0fd-49688ad5bc13)

- Step 13 : In More tab a donut chart was added which represents the revenue earned from subcategories.

  ![Screenshot 2024-08-08 091522](https://github.com/user-attachments/assets/058a7b71-f0ff-4bb9-9c56-6caef9e14e7b)

- Step 14 : Line and Clustered column chart was also added to represent the revenue earned which is represented by the orange ccolumns from subcategories with respect to the total cost required to produce the product which is represented with the blue line.

  ![Screenshot 2024-08-07 165018](https://github.com/user-attachments/assets/4f3631f0-2838-4daa-8222-649bd0e229c2)

- Step 15 : A gauge was also to provide the number of order delivered successfully that is not returned due to any reason with the starting range as 0 and end range as number of products totaly delivered.

  ![Screenshot 2024-08-08 091603](https://github.com/user-attachments/assets/1acfd473-9a2c-46f5-8495-243de727ce51)

- Step 16 : A " Q & A " chart was also added to act as interactive bot which gets the data the admin needs by getting the query as the keywords.The following image represents the Q & A tab when it is inactive 

  ![Screenshot 2024-08-08 091638](https://github.com/user-attachments/assets/262e3643-1478-4610-8f6b-be42f142c7c5)

- The following image represents the Q & A tab when it is actively displaying values
  
  ![image](https://github.com/user-attachments/assets/96d4b99a-c1d1-49ff-8408-c38252a75878)

  One can check for it correctness by cross checking with the selections of the slicer and data displayed in the visuals.

- Step 17 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Package handling

  (b) Services
  
  (c) Quality of product
  
  (d) Ease of online payment
  
  (e) Dispatching & delivery time 
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

