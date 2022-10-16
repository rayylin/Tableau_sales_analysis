#Tableau_sales_analysis
In this project, we are going to use Tableau to have a sales analysis

#Raw data & data preprocessing
We have two tables, PO data and customer data. We need to remove personal identifying information from data first (deidentification). We use python to achieve so.

![image](https://user-images.githubusercontent.com/58899897/196043531-b84543ce-a616-4e51-94ff-625be739593b.png)

Data after preprocessing

![image](https://user-images.githubusercontent.com/58899897/196043555-e1c4c419-e71c-4cbf-a4f6-4bc0704530d1.png)

![image](https://user-images.githubusercontent.com/58899897/196043568-3d43c11b-ea3a-4649-992e-5fd2468bdf69.png)

# Tableau dashboard

![image](https://user-images.githubusercontent.com/58899897/196043671-cede88d6-987a-4d49-a2f6-8402f7caf273.png)


How could we use Tableau to analyze data? We will use sales performance as an example.
The first picture is the revenue by product name and category.

![image](https://user-images.githubusercontent.com/58899897/196043873-a7b5a940-76a6-4d1d-8883-5eacda32d507.png)

We could compare the revenue and profit

![image](https://user-images.githubusercontent.com/58899897/196043951-42f32281-1083-4cb9-bb6f-f989b0cd693d.png)

From this picture we could tell that product 8 has higher revenue than those of product 6 and 4, but the revenue of product 8 is lower than those of product 6 and 4.
We could use "keep only" to remove unnecessary columns and focus on product 8.

![image](https://user-images.githubusercontent.com/58899897/196044080-67497187-6684-470a-ac0c-4239b2455ea2.png)

From this picture we could see that product 8 performs well in every country except Italy. Again we could use "keep only" to focus on the performance of Italy.
We could use order date to review the performance of each year. From this picture we could see that product 8 profits in 2018 and 2019 and suffers a loss in 2020 and 2021. 

![image](https://user-images.githubusercontent.com/58899897/196044242-2467eec4-d76a-4d12-aba6-0a2c435e77cb.png)

However, the revenue is increasing. We need to review that the decrease in profit stems from the increase in costs or the decrease in unit price or quantity.
To address this issue, we add the quantity value.

![image](https://user-images.githubusercontent.com/58899897/196044652-f6413b49-9437-4d8b-a7ae-c8292b1e63ae.png)

We could see that the quantity increases, so the decrease in profit must come from the increase in costs or the decrease in unit price. However, we don't have much information for these two factors.

![image](https://user-images.githubusercontent.com/58899897/196044827-3800f08c-0c3f-44dd-9437-34debaed2cb6.png)




