## KPI - COVERAGE IN DAYS, STOCK VALUE
<img src="/KPI_COVERAGE/KPI_COV_1.png?raw=true"/>
Project description:

This KPI - COVERAGE IN WEEKS, STOCK VALUE dashboard may support inventroy planners to keep stock on the right level. 
Very simple visualtions focus on two main KPIs - value of inventory and coverage (rotation) of current inventory in days. Based on these dashboards planner may asses very easily if stock's evolution proceeds in the right way and launch countermeaures if necessary. 



### 1. MAIN OBJECTIVES FOR TOOL:

1. to present evolution of inventory value and coverage (rotation) simultanously
2. to present variables above using such slicers as:
   - date (year/month)
   - planner
   - supplier
   - plant
   - material
<img src="/KPI_COVERAGE/KPI_COV_2.png?raw=true"/>
<img src="/KPI_COVERAGE/KPI_COV_3.png?raw=true"/>
<img src="/KPI_COVERAGE/KPI_COV_5.png?raw=true"/>

3. to present quality of stock: to put it simply: comparison of shares of deadstock vs. fast moving goods (and something between them)
<img src="/KPI_COVERAGE/KPI_COV_4.png?raw=true"/>

### 2. MAIN TOOL'S RECEIVER:

1. Inventory Planners
2. Inventory Manager
     
### 3.  TOOLS/APPLICATION USED:

1. SAP S/4 HANA
2. POWER BI
3. POWER QUERY
4. EXCEL
5. VBA

Process and scheme of preparing:
Beginning of every month from SAP S/4 are downloaded HANA data as such:
1. current stock value
2. Usage value for last 12 months
for every material in chosen plants (with planners and suppliers accordingly). Then - through Power Query - data are presented on dashords.
After data cleansing process data are added to main Excel data base.

MODEL SCHEME:
<img src="/KPI_COVERAGE/KPI_COV-SCHEME.png?raw=true"/>
### 4.  FILE'S TYPES USED

1. .XLSB
2. .PBIX



For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

