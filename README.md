# Power-BI-Driven-Marketing-Campaign-Insights

This project uses Microsoft Power BI Desktop to Transform, load and visualize the data.<br/>
<br/>
<br/>

**DAX FORMULAS USED**

Total Purchase = SUM(ifood_df[No.CatalogPurchases]) + SUM(ifood_df[No.DealsPurchases]) + SUM(ifood_df[No.StorePurchases]) + SUM(ifood_df[No.WebPurchases])
![img1](https://github.com/user-attachments/assets/36e771be-9de9-48e3-bbef-a63643570796)

Target Response = 0.15* SUM(ifood_df[Response])

Campaign Profit = SUM(ifood_df[Z_Revenue]) - SUM(ifood_df[Z_CostContact])

% Success = (SUM(ifood_df[Response])) / (SUM(ifood_df[Campaign_Overall]))

<br/>
<br/>

**DATASET**
The dataset used is uploaded and the source is Kaggle.<br/>
<br/>
<br/>
Dashbord


![img2](https://github.com/user-attachments/assets/1d639fa1-9dd4-41a2-8759-1c8b541a3a76)

![Uploading img1.png…]()



