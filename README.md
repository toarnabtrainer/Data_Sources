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
* **Query-2:** List only those discounted product details along with discount amount and discounted price.
* **Query-3:** Against all products, display discount amount and discounted price. Fill with 0 where discount % is null.
* **Query-4:** List those category details which has no product.

**Lookup and Dimension Tables**<br>
Lookup Tables or Dimension Tables will have Primary Keys, will answer Who, What, Where, When and How<br>
Data Tables or Fact Table will have Foreign Keys, and will contain transactional data

**Operations on Budget Workbook:**<br>
Delete promote header, Delete first 3 rows as they are null, Promote first row as heading, Delete last total column, delete rows whose first column is containing “Total”, Unpivot month labelled rows, Change the data type of month column to date, Rename columns (Month and BudgetAmount), Select close and apply.<br>

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

![image](https://github.com/toarnabtrainer/Data_Sources/assets/111301975/15f25c0e-4634-4f49-bcbf-3d32f138c7ef)


<hr>
