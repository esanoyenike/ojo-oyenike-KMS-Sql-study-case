# ojo-oyenike-KMS-Sql-study-case
# Case Study Two (Kultra Mega Store Inventory SQL Study case)
#### Company Overview
Kultra Mega Stores (KMS), headquartered in Lagos, specialises in office supplies and
furniture. Its customer base includes individual consumers, small businesses (retail), and
large corporate clients (wholesale) across Lagos, Nigeria.
#### Objectives
1. To analytical business intelligence to support the Abuja division of KMS.
2. To achive the above using SQL.
#### Procedure
##### Step 1
1. Importing data into SQL Server.
2. Analysis the data with different sql queries.
3. Joining the two data in SQL
##### Analysis Results
1. The product category with the highest sales
   **Technology	(5984248.18)**
2. Top 3 regions in terms of sales.
   **West	  (3597549.270);
   Ontario	(3063212.476);
    Prarie	(2837304.605)**
3. Bottom 3 regions in terms of sales.
  **Nunavut	(116376.484)
  Northwest Territories	(800847.331);
  Yukon	(975867.376)**
4. The total sales of appliances in Ontario
   **Ontario:	Appliances,	202346.840**
5. The revenue from the bottom 10 customers.
     -I obsereved that the the sales made from the  bottom 10 cutomers were below 5.
    - The profit made from the transactions were alll negative.
    - The discount rate given to them were very low. There were some that were as low as 0.0099, 0.02, and 0.05.
    - Also, the shipping cost is moderate.
   - **Advise the management of KMS on what to do to increase the reveunue from the bottom 10 customers.**
   - The discount policy should be reviewed to number of product ordered. Discount as high 10%  can be given to customer that orders a certain number of product or the fresquncy of order   should also be considered.
6. KMS incurred the most shipping cost using which shipping method?
   **Delivery Truck	164.7300000000**
7. The most valuable customers and the products or services they typically purchase.
  -**Emily Phan	Technology	Office Machines	103652.487**
   - **Raymond Book	Technology	Copiers and Fax	51954.520**
   - **Dennis Kane	Technology	Copiers and Fax	49836.402**
  - **Jasper Cacioppo	Technology	Office Machines	45923.762**
  - **Grant Carroll	Office Supplies	Binders and Binder Accessories	45025.209**
  - **Clytie Kelty	Technology	Copiers and Fax	44344.399**
  - **Craig Carreira	Technology	Office Machines	41343.211**
  - **Alejandro Grove	Office Supplies	Binders and Binder Accessories	41199.121**
  - **Roy Skaria	Furniture	Bookcases	38092.340**
  - **Roy Phan	Technology	Office Machines	36853.449**
  - ** Office Machines, copier and fax, binders and binder accesories, bookcases.
    8. The small business customer had the highest sales.
    - **Dennis Kane	Small Business	75967.5932159424** 
9. The Corporate Customer who placed the most number of orders in 2009 – 2012 is Laurel Elliston
in customer segment, Corporate, he made the order on	2010-11-01,  and the sales made was 148.
10. The consumer customer was the most profitable.
      -**Emily Phan	in customer sehment,Consumer and the total profit of 34005.4400 was made.**
11. The customer that returned items, and what segment do they belong to.(The result will be provided in the SQL query)

12. If the delivery truck is the most economical but the slowest shipping method and
Express Air is the fastest but the most expensive one, do you think the company
appropriately spent shipping costs based on the Order Priority? Explain your answer

- The shipping cost pattern does not appear to be a clear reflection of the order priority. For instance, critical prders should be shiped through Express air and should have a highest cost due to the urgency in the order. In this order, the High priority order should follow, the the low and the not specified shpuld come last.

- Therefore, studing the data, it shows that the company did not appropraitely spend shipping costs based on the order priority. Express air was used to ship even products with low and not specified order priority as against the delivery truck that should have been used to safe cost.
