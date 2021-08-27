# Visualization

## My purpose

This work basically includes data visualization practices.The purpose of this repo is to share my case studies.Pandas, NumPy, Matplotlib, and Seaborn libraries are used.
I aim to constantly update the notebook file.

## Dataset

I'm parsing an e-commerce site known as a dataset.I store the data I parse in PostgreSQL and also analyze it in pandas.Although the time series of my data is very weak at the moment, I aim to grow this database regularly in the future.The parsing process currently consists of the following features.

0   Product_No
 1   Product_BreadCrum
 2   Product_MinCatagory
 3   Add_date
 4   Product_Name
 5   Product_Brand
 6   Product_Free_Shipping
 7   Product_Org_Price
 8   Product_Dsc_Price
 9   Product_Cart_Price
 10  Product_insize
 11  Product_outsize
 12  Product_Ratings
 13  Product_url
 14  Product_img_url
 15  id

To explain the Product_Org_Price, Product_Dsc_Price, Product_Cart_Price features;

![](https://github.com/imertekin/Visualization/blob/main/product_cart.png)

As seen picture dsc_price is the **main price** and cannot be **null**.

## Goals in the future

1- Expanding the dataset regularly <br/>
2- Adding new features to the Dataset(e.g. marchent information and stock information)<br/>
3- To make meaningful analyzes with the growth of the data set and to follow the price changes<br/>
