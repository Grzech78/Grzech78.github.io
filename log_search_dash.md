## LOGISTICS SEARCHENGINE DASHBOARD

DOWNLOAD MOVIE - LINK AT THE BOTTOM

[![Watch the video](https://raw.githubusercontent.com/Grzech78/Grzech78.github.io/main/LPB_1_EN_small.png)]

Project description:

At the market customers use and are aware about market references only, derived from official Excel pricelist. However behind these market references exist internal references that may vary from market reference due to a product version or evolution, slight technical modifications, various assembly plants etc. Thus when a customer place an order, for example for offical material reference "child_bike_18_GR" it has to be translated by special SAP substitution table into "child_bike_18_GR_ver1" which is active for production, sales and so on.
Additionally every market reference may have several internal references with their:
1. product life cycle - design phase, active phase, withdrawal phase, deletion phase and so on (SAP distribution-chain-specific material status)
2. main distribution warehouse 
3. inventory planner who responsible for avaiability of internal reference for local market

### 1. MAIN OBJECTIVES FOR TOOL:

in few dashboards of POWER BI based mainly on TXT files downloaded from SAP S/4 (update triggered by VBA code):

1. return active valid internal reference
2. return current SAP distribution-chain-specific material status with graphic explanation providing clear visibility if reference can be ordered
3. return current main distribution warehouse
4. return current inventory planner responsible for internal reference

DASHBORDS RETURNING ACTIVE INTERNAL REFERENCES, SALES STATUS, INVENTORY PLANNER AND MAIN DISTRIBUTION WAREHOUSE:
<img src="/LPB_1_EN.png?raw=true"/>
<img src="/LPB_2_EN.png?raw=true"/>
<img src="/LPB_3_EN.png?raw=true"/>

DASHBOARDS RETURNING GENERAL OVERVIEW OF SALES STATUSES
<img src="/LPB_4_EN.png?raw=true"/>

MODEL VIEW OF POWER BI.PBIX
<img src="/LPB_5_EN.png?raw=true"/>

MODEL SCHEME
<img src="/SCHEME.png?raw=true"/>

### 2. MAIN TOOL'S RECEIVER:

1. Customer Service Team
2. Product Managament Team
3. Sales Team
4. Technical Support Team
     
### 3.  TOOLS/APPLICATION USED:

1. SAP S/4 HANA
2. POWER BI
3. POWER QUERY
4. EXCEL
5. VBA
6. ABAP

### 4.  FILE'S TYPES USED

1. .XLSB
2. .TXT
3. .PBIX


[![Watch the video](https://raw.githubusercontent.com/Grzech78/Grzech78.github.io/main/LPB_1_EN_small.png)]
(https://raw.githubusercontent.com//Grzech78/Grzech78.github.io/main/mov.mp4)

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
