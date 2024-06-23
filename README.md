# Excel_PowerBI_Tableau_Data_Sources

**GitHub Link:**<br>
https://github.com/toarnabtrainer/Data_Sources/<br>
or<br>
https://tinyurl.com/yc7czrzr<br>

**GMeet Link:**<br>
https://meet.google.com/ugx-iskt-vbc

**MS-Teams Link:**<br>
https://teams.microsoft.com/l/meetup-join/19%3ameeting_MGQ0MWQ0MGItYzEzNS00OTdjLThlYmMtOGMzNmQ2YWUwNWIz%40thread.v2/0?context=%7b%22Tid%22%3a%22ff6114ce-6904-43f4-83a2-11ea43d58b83%22%2c%22Oid%22%3a%2240936497-561b-4e40-95f5-1655f81c8574%22%7d<br>
Or<br>
https://tinyurl.com/2s3yxjnr

**HTML Color Codes:**<br>
https://htmlcolorcodes.com/

**PowerBI Download Link:**<br>
https://www.microsoft.com/en-us/download/details.aspx?id=58494

**PDF Link on the Cloud:**<br>
https://www.indiapost.gov.in/VAS/DOP_PDFFiles/Civillistnew.pdf

**Web Portal Link:**<br>
https://www.contextures.com/xlsampledata01.html

**SharePoint Site Link for OnLine List: (List_Project_Tasks)**<br>
https://totsoltechnologies.sharepoint.com/sites/ABCofSharePoint

**SQL Server Database:**<br>
*	Server - Sqlplesk7.securehostdns.com,1234
*	user id – codingskills
* password - Babi@2292
* database - codingskills
* Sample Table - registration, seminar, colleges
* Data Fetching –
  *	Direct Query - select * from dbo.registration
  *	Import

**Tutorial and Official Documentation on MS-Power BI Link:**<br>
https://docs.microsoft.com/en-us/power-bi/desktop-create-and-manage-relationships

**MS-Power BI Data Compresion Capability:**<br>
* **PracticeData1.xlsx ->** Size 705 KB
* **ClassWork.pbix (After all data import) ->** Size 64 KB
* **ClassWork.pbix (After Unpivot) ->** Size 56 KB
* **ClassWork.pbix (After Country_Sales Query creation) ->** Size 61 KB
* **ClassWork.pbix (After Total_Sales_PQEW) ->** Size 65 KB
* **ClassWork.pbix (After Total_Sales_PBIDW) ->** Size 66 KB
* **ClassWork.pbix (After Total_Sales measure creation) ->** Size 66 KB
* **ClassWork.pbix (After Total_Sales_Measure column creation) ->** Size 67 KB

**Table Formats:**<br>
<pre>
* Wide Format (Unstacked Format) ------------------------> Long Format (Stacked Format)
                                     Unpivot Operation

* Long Format (Stacked Format) ------------------------> Wide Format (Unstacked Format)
                                     Pivot Operation
</pre>

**Assignment on Merge operations:**<br>
* **Query-1:** List those product details which has no discount.
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/eb4c8b10-b987-4991-904a-d34bc240cca6)
* **Query-2:** List only those discounted product details along with discount amount and discounted price.
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/050f2529-37db-471f-ac10-ff18360a74a5)
* **Query-3:** Against all products, display discount amount and discounted price. Fill with 0 where discount % is null.
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/a5eb2259-e78e-4a1d-94c1-18d2da8c7ffe)
* **Query-4:** List those category details which has no product.
<br>**Output:** ![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/6f144d15-1dd3-41e8-828e-574c07f2af75)
  
**Lookup/Dimension Tables and Data/Fact Tables:**<br>
Lookup Tables or Dimension Tables will have Primary Keys, will answer Who, What, Where, When and How<br>
Data Tables or Fact Table will have Foreign Keys, and will contain transactional data

**Operations on Budget Workbook:** <br>
* Delete the promoted header
* Delete first 3 null rows
* Promote the first row as a header
* Delete last total column
* Filter out rows from the first column containing “Total”
* Unpivot month columns labelled from Jan to Dec
* Rename new created columns to Month and BudgetAmount
* Change the data type of Month column to Date
* Select close and apply <br>

**Data Relationships for the Budget Project:**<br>
* Sales(CustomerKey) -> Customer(CustomerKey)<br>
* Sales(OrderDate) -> Calendar(Date)<br>
* Sales(ProductKey) -> Product(ProductKey)<br>
* Sales(SalesTerritoryKey) -> Territories(SalesTerritoryKey)<br>
* Budget(ProductKey) -> Product(ProductKey)<br>
* Budget(Month) -> Calendar(Date)<br>

**Suggested Tables Summaries (After filtering on Year 2016):**<br>
*	**Table1:** Calendar[Year], Calendar[Month], Sum of Sales[SalesAmount] 
*	**Table2:** Calendar[Year], Calendar[Month], Sum of Budget[BudgetAmount]
*	**Table3:** Territories[Country], Sum of Sales[SalesAmount]
*	**Table4:** Calendar[Year], Calendar[Month], Sum of Sales[SalesAmount], Sum of Budget[BudgetAmount]

<hr>

# Different Join Operations:

![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/5715ba40-1546-40d7-984f-3002d411cc57)

<hr>

![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/e2a3d88f-e1ab-4459-b1ec-28fce08a21b1)

<hr>
