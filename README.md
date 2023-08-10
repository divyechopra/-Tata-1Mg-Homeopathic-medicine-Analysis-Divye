# -Tata-1Mg-Homeopathic-medicine-Analysis-Divye <img src=https://notion-emojis.s3-us-west-2.amazonaws.com/prod/svg-twitter/1f48a.svg width="48" height="48">

## Introduction
In the modern era, there's a growing interest in homeopathic medicine due to its holistic approach to healing. This project aims to analyze data related to homeopathic medicine products, including benefits, pricing, brands, ratings, and ingredients.

## Problem aimed to Solve
This project helps entrepreneurs estimate costs for a homeopathic store and select relevant products. It uses data analysis to empower informed decisions, aiming to create an interactive dashboard for cost evaluation and product selection based on benefits.

##  <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual**

| Files/Folder| Description |
| ------------- | ------------- |
| **Excel file** | This file provides you two the insights and the analysis.  |
| **Python File** | This contains the .ipynb file related to the web scrapping part.  |
| **Other Excel file** | These files (merged_data.xlsx, medicine_details_final.xlsx, merged_data.xlsx) have the scarpped data from the 1 Mg website. |
| **Project Prestation** | This file have the dashboards and insights of the project. |

## Data Description

- **Table - 1**: *medicine_name*

Column Name           | Description
----------------------|-----------------------------------------------------------
name                  | Name of the medicine
size_of_the_bottle    | Size of the medicine bottle or pack
MRP_of_the_bottle     | Industry of the company from which the job is
price_of_the_bottle   | Selling price of the bottle
1mg_url               | 1mg url where the medicine sold

<img width="276" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/40efdc74-f8e6-4ee7-a7c3-7ce4d2c05df0">

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/e607b8b0-ea18-4dda-9b95-83ed99f323ea">

- **Table - 2** : *medicine_details*

Column Name         | Description
--------------------|-------------------------------------------------
name                | Name of the medicine
brand_name          | Brand name of the medicine
key_benefits        | Key Benefits area (Hair, eye, joint, skin)
key_ingredients     | Ingredient of medicine
rating              | User rating of the medicine
number_of_rating    | Number of people rated that product

<img width="517" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/35bde19d-8e7a-428e-b38b-6414303be95a">

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/711af748-c78f-459f-af04-03819899220d">


##  <img src="https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif"  width="48" height="48"> Analysis

- Number of medicine available of different benefit area.
- Price range of medicine for each benefit area.
- Brand specialization(Key Benefits) of each area.
- Average price, min price , max price and number of products for each brand.
- Average number of rating for each brand in their specialization products where  the number of rating is not NULL.
- Maximum number of times ingredient used in each benefit area.
- Average cost for ingredients.
- Most used ingredient
- Which brand has most greater than 4 point review medicine?

<br>

## <img src="https://user-images.githubusercontent.com/106439762/181937125-2a4b22a3-f8a9-4226-bbd3-df972f9dbbc4.gif" width="48" height="48" > Methodology

- Scraped the data with the help of Python BeautifulSoup librariy.

### For Table - 1

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/e4e4197f-3402-4c2f-8e51-45a4fa439cf6">

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/07370284-62ff-4260-9dbd-801eae2c6f6d">

### For Table - 2

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/d9de285d-650b-47c1-b9ad-bfd97c10bb0b">

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/76813c27-71f8-4979-b267-ece33c2e1729">




- Used Pandas for the data framing part.
<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/df259eb7-ed2a-4a88-a228-7cd830c73740">

<img width="900" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/c55f970c-a355-4476-afe8-805ca09fa1f5">


- Analysis was done with the help of Pandas and Excel.



- Insights were generated from the above analysis.

  1). The number of medicines in the benefits area Eye is highest.
  ![image](https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/d5a73475-3445-4549-b4de-5bba03278f32)
  
  2). SBL Pvt Ltd has the highest average number of ratings, i.e. ₹ 559.12, in the Hair-benefit area.
  
  ![image](https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/1449fe0a-7733-4a51-8f61-30375f9085d9)
  
  3). The brand SBL Pvt Ltd has most greater than 4-point review medicines.
  
  ![image](https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/f37489ad-d410-450c-99e3-1e1f40992289)

  4). Natrum Muriaticum in Heart key benefit area, is the most used Ingredient overall.
  
  ![image](https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/243d2dbc-bb34-467f-a6c6-109080d6fe9b)

- Guesstimation is done for estimating the cost of opening the medical store
  <img width="960" alt="image" src="https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/0d7ede2c-e952-4ecb-babc-e4caef07cec9">

  

- Excel is used for **dashboard** and data visualization.
## Dashboard

![image](https://github.com/divyechopra/-Tata-1Mg-Homeopathic-medicine-Analysis-Divye/assets/122443219/47d8c396-f3da-4198-b87d-599bf66188e2)


## <img src="https://user-images.githubusercontent.com/108053296/185796560-b5035cfb-d8e4-4b61-b6fe-e0e75487bd94.gif" width="48" height="48" > Conclusions



# Insights from the Dashboard

- The most used ingredient is Belladonna.
- The number of medicines in the benefits area Eye is highest.
- SBL Pvt Ltd has the highest average number of ratings in the Hair-benefit area.
- The brand SBL Pvt Ltd has most greater than 4-point review medicines.
- SBL Pvt Ltd and Bjain Pharmaceutical Pvt Ltd are the two brands that are used most among the benefit areas.
- The Brand SBL Pvt Ltd has the highest number of medicines of where a number of ratings is present.
- Most rated medicine is from the Eye benefit area.
- The highest number of medicine, which are rated above 3.5, is from the Eye benefit area.
- Medicines of Eye benefit area would be recommended to purchase or from the brand SBL Pvt Ltd.

# Challenges and learnings

- **Website Ban**: Faced repeated bans on the 1Mg official website during data scraping attempts.
- **Google Colab Solution**: Resolved the issue by migrating scraping operations to Google Colab.
- **Extended Scraping Time**: Extracting details of each medicine took more time than anticipated.
- **Duplicate Data Issue**: Encountered delays due to duplicate data in the scraping process.
- **Learning Efficiency**: Gained insights into optimizing scraping methods for speed and accuracy.

# Conculsion

Despite challenges in data scraping and extended collection time, this project recommends prioritizing "Eye" benefit area medicines and considering products from SBL Pvt Ltd for a homeopathic store. The experience underscores the significance of adaptability, efficiency, and meticulous analysis in informed decision-making for the retail of homeopathic medicine.
























