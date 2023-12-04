# Customer Segmentation Using RFM and Cohort Analysis

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011
for a UK-based and registered non-store online retail. 

Before starting the RFM Analysis, we did some analysis regarding the distribution of Orders, Customers and Countries,
These analysis help the company develop its sales policies and contribute to the correct use of resources.

As what you will see, the UK not only has the most sales revenue, but also the most customers.
Since the majority of this data set contains orders from the UK, we can explore the UK market further by finding out
what products the customers buy together and any other buying behaviors to improve our sales and targeting strategy.




<img width="744" alt="Screenshot 1445-05-20 at 6 40 10 PM" src="https://github.com/atheermoh/Customer-Segmentation-Using-RFM-and-Cohort-analysis-/assets/51926875/504f6af8-92f6-42e9-8860-b13efc8825a4">


We started applying the RFM Analysis, a customer segmentation technique based on customers' past purchasing behavior.

We have calculated RFM (Recency, Frequency, and Monetary) for each customer.
<img width="408" alt="Screenshot 1445-05-20 at 6 48 14 PM" src="https://github.com/atheermoh/Customer-Segmentation-Using-RFM-and-Cohort-analysis-/assets/51926875/190864fa-6c27-4f98-85bd-26888f39336c">


then, we have created an RFM Segmentation Table where we segment our customers by using the RFM table.
For example, we labeled the best customer as "Best Customers" and the lost customer as "Almost Lost".
<img width="929" alt="Screenshot 1445-05-20 at 6 28 24 PM" src="https://github.com/atheermoh/Customer-Segmentation-Using-RFM-and-Cohort-analysis-/assets/51926875/087c8372-4e98-42d0-a2be-c8d93cb4208a">

We did some K-mean clustering and we fitted our model by choosing three clusters. we assigned the labels as Silver, Bronze and Gold loyality.
We can see, the most customers have Bronze loyality.
<img width="929" alt="Screenshot 1445-05-20 at 6 28 24 PM" src="https://github.com/atheermoh/Customer-Segmentation-Using-RFM-and-Cohort-analysis-/assets/51926875/4373f761-cf94-45af-b100-5d80e47639d9">


Here we can see the segmentation of the clusters by pairplot with each label. 
<img width="874" alt="Screenshot 1445-05-20 at 6 32 17 PM" src="https://github.com/atheermoh/Customer-Segmentation-Using-RFM-and-Cohort-analysis-/assets/51926875/16c0e906-08d5-47af-9c3e-7281addc1cf5">


Finally we have the crosstabulation results, here is the count of observations for each combination of 'Kmeans_Label' and 'RFM_Scores_Segments'. 
<img width="772" alt="Screenshot 1445-05-20 at 6 33 26 PM" src="https://github.com/atheermoh/Customer-Segmentation-Using-RFM-and-Cohort-analysis-/assets/51926875/7b94cee6-24f0-4c1c-be29-b2309fb02b67">









