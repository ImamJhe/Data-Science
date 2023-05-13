## This project will predict Melbourne house price using many machine learning

Liniear Regression Normalized <br>
Liniear Regression <br>
Ridge Model <br>
RandomForestClassifier <br>
XGBClassifier <br>

### About Data

<pre>
Some Key Details
Suburb  : Suburb
Address : Address
Rooms   : Number of rooms
Price   : Price in Australian dollars

Method:
S   - property sold;
SP  - property sold prior;
PI  - property passed in;
PN  - sold prior not disclosed;
SN  - sold not disclosed;
NB  - no bid;
VB  - vendor bid;
W   - withdrawn prior to auction;
SA  - sold after auction;
SS  - sold after auction price not disclosed.
N/A - price or highest bid not available.

Type:
br        - bedroom(s);
h         - house,cottage,villa, semi,terrace;
u         - unit, duplex;
t         - townhouse;
dev site  - development site;
o res     - other residential.

SellerG       : Real Estate Agent
Date          : Date sold
Distance      : Distance from CBD in Kilometres
Regionname    : General Region (West, North West, North, North east …etc)
Propertycount : Number of properties that exist in the suburb.
Bedroom2      : Scraped # of Bedrooms (from different source)
Bathroom      : Number of Bathrooms
Car           : Number of carspots
Landsize      : Land Size in Metres
BuildingArea  : Building Size in Metres
YearBuilt     : Year the house was built
CouncilArea   : Governing council for the area
Lattitude     : Self explanitory
Longtitude    : Self explanitory
<pre>


Conclusion :

|    Model Machine Learning     |      MAE	 |      RMSE      | R2-score   |
| ----------------------------- | -------------- | -------------- | --------- |
| XGBRegressor                  | 157005.837902  | 236259.353358  | 0.854719  |
| RandomForestClassifier        | 219308.285714  | 354336.009620  | 0.673216  |
| Linear Regression             | 276635.670855  | 390453.838965  | 0.603202  |
| Ridge                         | 278033.214349	 | 390930.162533  | 0.602234  | 
| Linear Regression Normalized  | 278037.143548  | 390933.299419  | 0.602227  |
