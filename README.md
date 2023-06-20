# Excel_PowerBI_Tableau_Data_Sources

**GitHub Link:**<br>
https://github.com/toarnabtrainer/Excel_PowerBI_Tableau_Data_Sources/<br>
or<br>
https://tinyurl.com/yc7czrzr<br>

**Online Session MS-Teams Link for all sessions:**<br>
**Training link for Morning Batch - 1:**<br>
* https://teams.microsoft.com/l/meetup-join/19%3ameeting_MTJjMzNlYzktODllMi00YjU0LTk0OWQtZDA2MjQ3ODU3NmM1%40thread.v2/0?context=%7b%22Tid%22%3a%22ae6b1153-fd4c-4df1-8e27-fb0356c98817%22%2c%22Oid%22%3a%220dd286f1-facc-4c2b-8c8d-2b8431f8dddf%22%7d

**Training link for Afternoon Batch - 2:**
* https://teams.microsoft.com/l/meetup-join/19%3ameeting_NzViNTI4NDktMWI2Mi00ODYzLWFmY2EtMjUxZjRhODlmOGQ3%40thread.v2/0?context=%7b%22Tid%22%3a%22ae6b1153-fd4c-4df1-8e27-fb0356c98817%22%2c%22Oid%22%3a%220dd286f1-facc-4c2b-8c8d-2b8431f8dddf%22%7d

**HTML Coloe Codes:**<br>
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

**Lookup and Dimension Tables**<br>
Lookup Tables or Dimension Tables will have Primary Keys, will answer Who, What, Where, When and How<br>
Data Tables or Fact Table will have Foreign Keys, and will contain transactional data

**Assignment on Merge operations:**<br>
* **Query-1:** List those product details which has no discount.
* **Query-2:** List only those discounted product details along with discount amount and discounted price.
* **Query-3:** Against all products, display discount amount and discounted price. Fill with 0 where discount % is null.
* **Query-4:** List those category details which has no product.

**Data Relationships for the Budget Project**<br>
* Sales(CustomerKey) -> Customer(CustomerKey)<br>
* Sales(OrderDate) -> Calendar(Date)<br>
* Sales(ProductKey) -> Product(ProductKey)<br>
* Sales(SalesTerritoryKey) -> Territories(SalesTerritoryKey)<br>
* Budget(ProdyctKey) -> Product(ProductKey)<br>
* Budget(Month) -> Calendar(Date)<br>

**DAX Functions:**<br>
* TotalSales = SUM(RN_East1[EastSales])  // SUM(Coolumn Name)<br>
* AverageSales = AVERAGE(RN_East1[EastSales])  // AVERAGE(Column Name)<br>
* CountSales = COUNT(RN_East1[EastSales])   // COUNT(Column Name)<br>
* MaxSales = MAX(RN_East1[EastSales])   // MAX(Column Name)<br>
* MinSales = MIN(RN_East1[EastSales])   // MIN(Column Name)<br>
* SDSales = STDEV.S(RN_East1[EastSales])   // STDEV.S(Column Name)<br>
* VarSales = VAR.S(RN_East1[EastSales])   // VAR.S(Column Name)<br>
* SDSales1 = SQRT(VAR.S(RN_East1[EastSales]))   // SQRT(VAR.S(Column Name))<br>
* VarSales1 = STDEV.S(RN_East1[EastSales])^2   // STDEV.S(Column Name) ^ 2<br>
* GSTSalesSumX = SUMX(RN_East1, RN_East1[EastSales] * 0.18)   // SUMX(Table Name, Expression)<br>
* GSTSalesAvgX = AVERAGEX(RN_East1, RN_East1[EastSales] * 0.18)   // AVERAGEX(Table Name, Expression)<br>
* GSTSalesMinX = MINX(RN_East1, RN_East1[EastSales] * 0.18)   // MINX(Table Name, Expression)<br>
* GSTSalesMaxX = MAXX(RN_East1, RN_East1[EastSales] * 0.18)   // MAXX(Table Name, Expression)<br>
* CountOfRows = COUNTROWS(RN_East1)   // COUNTROWS(Table Name)<br>
* CountXOfRows = COUNTAX(RN_East1, RN_East1[EastSales] * 0.18)   // COUNTAX(Table Name, Expression)<br>
* CalculateMinGST = CALCULATE([TotalSales] * 0.18, RN_East1[Month] = "AUG", RN_East1[Product] = "P013")   // CALCULATE(Expression, Filter1, Filter2, ...)<br>
* FilterMinGST = MINX(FILTER(RN_East1, RN_East1[Month] = "AUG"), [TotalSales] * 0.18)   // FILTER(Table Name, Filter)<br>
* TotalSalesAll = CALCULATE(sum(RN_East1[EastSales]), ALL(RN_East1))   // ALL(Table Name[<Column>])<br>


