# Ecommerce

### Dashboard Link : https://github.com/Ashwin02013/Power-BI/blob/main/ecommerce.pbix

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

![Screenshot 2024-08-07 123723](https://github.com/user-attachments/assets/5407fe49-dbdd-4a47-9ba7-f60afc7fc8f5)

- Step 6 : Five card visuals were added to the canvas, Representing Total Revenue , Total Profit , Total Order,Average Ratings & Total Products as shown in the above picture.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           Although, by default, while calculating average, blank values are ignored.

- Step 7 : A Line chart was added to the report design area representing the Total Revenue for years and the trend line and forecast was active to predict the future revenue as follows.
The line chart was drilled down to quarters ( Q1 - Q4 )

![Screenshot 2024-08-07 123915](https://github.com/user-attachments/assets/838d13f3-8bdf-45c2-b807-d32a2809cdb3)

Line chart drilled down to months ( JAN – DEC )

![Screenshot 2024-08-07 124158](https://github.com/user-attachments/assets/5f95a30b-b54e-4ade-ab8a-64aab2cc915b)

Line chart drilled down by weektype ( WEEKDAY , WEEKEND )

![Screenshot 2024-08-07 124241](https://github.com/user-attachments/assets/5735e924-822e-480e-9593-83e54488d9bf)

- Step 8 : A Stacked bar Chart was also added to the report design area representing the Top N number of product used by sub cateogory and the corresponding revenue of it.

  ![Screenshot 2024-08-07 165126](https://github.com/user-attachments/assets/eef9e911-7586-4874-9236-e7658519d51d)

- Step 9 : A map was also added to the report design area representing the location where the products were delivered.  

  ![Screenshot 2024-08-07 165457](https://github.com/user-attachments/assets/b8a8775b-f489-4e27-affa-9acbfbdc34ab)

   The above map style was changed from light to aerial to match the dark theme and the locations can also be zoomed by clicking the plus icon and it is shown in the image as follows.

- The following image is zoomed only by once
 
  ![Screenshot 2024-08-07 165744](https://github.com/user-attachments/assets/31696323-03d2-48e6-91cf-a311032562c2)
   
- The following image is zoomed in again by once

  ![Screenshot 2024-08-07 170153](https://github.com/user-attachments/assets/4c1794b7-7aaf-4e5b-aa5b-dba07ffcb3aa)

- This could be zoomed in to street of a city 

   ![Screenshot 2024-08-07 170306](https://github.com/user-attachments/assets/cdfe58da-d5d4-4b1d-88a0-24352926b9fe)

- Step 10 : A Rectangle was inserted to replicate the functionality of a task bar and buttons ( Blanks ) were added and images were inserted from " icon-8 " which contained four blanks representing " 1 - logo " followerd by a slicer with search which replicates the search tab ,Then " 2 - Expand "," 3 - Favourite ", " 4 - Cart ".

  ![Screenshot 2024-08-08 091119](https://github.com/user-attachments/assets/0802dd64-f226-4915-9f54-146d36f44d9c)

- Step 11 : More tab , Favourite tab , Cart tab were created in correspondence with above mentioned tab names.

  ![Screenshot 2024-08-08 091335](https://github.com/user-attachments/assets/25877f0e-db86-4100-a28c-fd858f14f950)

-  " 1 - logo " tata cliq logo was downloaded as png and was filled 0 transparency to make atmost visible,"
-  " Search " A slicer is added to replicate the search 
-  " 2 - Expand " Expand symbol was added to show more options for the selected products, A slicer was added with search option to replicate the activities of the search bar . In the following image one can notice the data in visuals display the value corresponding to the search synced from " Home " page and the search bar in the " More " page also has the same values.
- The following image is the more tab with the search tab actively selected for a particular product that is "Samsung Mobile"

    ![Screenshot 2024-08-07 131615](https://github.com/user-attachments/assets/ccc3be15-9719-4093-8d32-95d2415e24c4)

- Before selecting a product , When the keyword for the product is selected it provides category under which the product comes as shown in image below.

    ![Screenshot 2024-08-07 131100](https://github.com/user-attachments/assets/e535a521-3126-40a2-b1cf-9afd6b3e227c)

- As shown in the above picture the " Samsung " keyword searched comes under the  " Phones and Tablet " category and when the down arrow is clicked it display the subcategory that has the product samsung as follows

   ![Screenshot 2024-08-07 131127](https://github.com/user-attachments/assets/f0a6a309-4077-47d5-b277-d366b8dc525e)

- On repeating the same process , It display the variety of mobiles which has the keyword " Samsung " as follows

  ![Screenshot 2024-08-07 131232](https://github.com/user-attachments/assets/52f9caee-dcbb-470e-ae2d-04ed14639d5e)

- As shown in the above image there are two products which has the " Samsung " keyword in it and the background visuals display the same data of all the products combined . When the product is selected by clicking the checkbox the visuals in the background will display the values of the particular product selected , That is " Samsung Galaxy A02 - 64B HDD - 3RB RAM Smartphone " as follows.

  ![Screenshot 2024-08-07 131306](https://github.com/user-attachments/assets/f9b0e87f-66c8-4423-8e2e-02425c4d4f6a)

- " 3 - favourite " favourite icon  was added which navigate to a tab containing a screenshot of the actual favourite tab of "tatacliq" website to replicate the theme of it.

    ![Screenshot 2024-08-08 091903](https://github.com/user-attachments/assets/83da08e7-d397-49c8-b8d1-1038007b1c9a)

- " 4 - Cart " Cart icon  was added which navigate to a tab containing a screenshot of the actual Cart of " tatacliq " website to match the theme of it .

    ![Screenshot 2024-08-08 092135](https://github.com/user-attachments/assets/54a8561b-64de-4b0d-95af-f1ff73b80c48)

- Step 12 : More tab was inserted with four slicers representing year , month , location & rating . The following image is the screenshot of the tab with zero filters selected.

    ![Screenshot 2024-08-07 131656](https://github.com/user-attachments/assets/4321875b-42b8-463a-9022-cec5238091be)

- The following image is the more tab with all filters that is slicer active (" Year " is set to 2020 , " Location " is set to North East, " Month " is set to May , " Rating " is set to All)

  ![Screenshot 2024-08-07 131905](https://github.com/user-attachments/assets/cec61f87-23da-4bd5-a103-317452c7c00d)

- Step 13 : In More tab a donut chart was added which represents the revenue earned from subcategories.

  ![Screenshot 2024-08-08 091522](https://github.com/user-attachments/assets/9ca1f305-1a90-451f-96ab-5118e098c49c)

- Step 14 : Line and Clustered column chart was also added to represent the revenue earned which is represented by the orange ccolumns from subcategories with respect to the total cost required to produce the product which is represented with the blue line.

  ![Screenshot 2024-08-07 165018](https://github.com/user-attachments/assets/cf68aaaf-8aa2-41e4-8484-05225f81b1eb)

- Step 15 : A gauge was also to provide the number of order delivered successfully that is not returned due to any reason with the starting range as 0 and end range as number of products totaly delivered.

  ![Screenshot 2024-08-08 091603](https://github.com/user-attachments/assets/2c88a4b2-da45-4ec3-8ea1-395b24184e41)

- Step 16 : A " Q & A " chart was also added to act as interactive bot which gets the data the admin needs by getting the query as the keywords.The following image represents the Q & A tab when it is inactive 

  ![Screenshot 2024-08-08 091638](https://github.com/user-attachments/assets/0a946a9c-2633-46be-a716-147c96fcb76b)

- The following image represents the Q & A tab when it is actively displaying values
  
  ![Screenshot 2024-08-07 133143](https://github.com/user-attachments/assets/17ca7b4f-751a-4090-a70d-8a5637e2b182)

  One can check for it correctness by cross checking with the selections of the slicer and data displayed in the visuals.

- Step 17 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Package handling

  (b) Services
  
  (c) Quality of product
  
  (d) Ease of online payment
  
  (e) Dispatching & delivery time 
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

