# COFFEE_SALES_DASHBOARD
Visualizing Coffee Sales using excel pivot table

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## PROJECT DESCRIPTION
This work is aim to gain insight from coffee sales data. The dataset covers sales from 2019 to 2022. I created a dashboard which summarizes core thing needs to be focused on. 

## FUNCTION USED 
The data in csv (Comma Separated Value) form with three worksheets. They are "orders" , "customer" and "products". These worksheets have some common feature (columns) which can be shared to get new columns. The following are functions used in the project :-  

<b>Vlookup</b> - I used this function for maching country from "orders" worksheet to "customers" worksheet.

      =VLOOKUP(C2,customers!$A$2:$G$1001,7,FALSE)
      
<b>IndexMatch</b> - This one is nested function. used to get coffetype from "preoducts" worksheet to "orders" worksheet.

      =INDEX(products!$A$1:$G$49,MATCH(orders!$D2,products!$A$3:$A$49,0),MATCH(orders!I$1,products!$A$1:$G$1,0))

![IMAGE](https://github.com/Henamen21/COFFEE_SALES_DASHBOARD/blob/436802c0f5a2a999edaf0e58ee5fa2cae41b17d5/all_in_one.PNG)

### 🤝 Connect with me:

<a href="https://www.linkedin.com/in/henok-solomon-a3b537206"><img align="left" src="https://raw.githubusercontent.com/yushi1007/yushi1007/main/images/linkedin.svg" alt="Yu Shi | LinkedIn" width="21px"/></a>
<a href="https://medium.com/@heneyr24"><img align="left" 
src="https://raw.githubusercontent.com/yushi1007/yushi1007/main/images/medium.svg" alt="Yu Shi | Medium" width="21px"/>
</a>
# 
