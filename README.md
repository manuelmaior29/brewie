# brewie

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Model](#model)
  
## Overview
After getting a coffee-making machine there are a lot of situations in which the extracted coffee does not end up to our expectations. Most of the time, this is encountered when trying a new type of coffee. Some of us enjoy a balanced taste with slight bitterness while others prefer to drink a slightly acid coffee. Considering this, the idea of developing an ML-based system, that could aid the extraction process, specifically providing tips for adjusting parameters from _grind size_, _coffee quantity_ and _extraction time_ up to _coffee origin_, in order to achieve the desired coffee taste.
<br />
![alt text](images/coffee-icon.jpg)
<a href="https://www.vecteezy.com/free-vector/cappuccino">Cappuccino Vectors by Vecteezy</a>

## Data
Given that the application might be rather coffee machine dependent, the data used for implementing an ML-based, extraction settings optimization system, would be defined on the _Sage's the Barista Express™_ machine (since this one is close at hand for me).

### Variables
|Type|Name|MU|Data Type|Description|
|---|---|---|---|---|
|Dependent|Grind size setting|index|integer|The main adjustment value made on the grinder|
|Dependent|Grind size setting burr|index|integer|The adjustment value made on the grinder burr|
|Dependent|Extraction time|seconds|integer|The time passed from the first drop of coffee until the water is stopped|
|Dependent|Extraction quantity|grams|float|The quantity of water passed through coffee|
|Dependent|Coffee quantity|grams|float|The quantity of coffee used for extraction|
|Dependent|Distribution by side tap|flag|boolean|Whether the coffee was distributed in the portafilter by side tap|
|Dependent|Distribution by settling|flag|boolean|Whether the coffee was distributed in the portafilter by settling|
|Dependent|Distribution by nsew|flag|boolean|Whether the coffee was distributed in the portafilter by _nsew_ technique|
|Dependent|Distribution by stockfleth|flag|boolean|Whether the coffee was distributed in the portafilter by _stockfleth_ technique|
|Dependent|Distribution by WDT|flag|boolean|Whether the coffee was distributed in the portafilter by _WDT_ technique|
|Dependent|Distribution by spinning distribution tool|flag|boolean|Whether the coffee was distributed in the portafilter by spinning distribution tool (placed on top of the portafilter and spinned)|
|Independent|Coffee origin|-|string|The region from which the coffee was harvested|
|Independent|Coffee time since roast|days|integer|The time passed since the coffee was roasted|
|Independent|Coffee processing type|-|string|The method used for processing the coffee beans after harvesting|
|Independent|Coffee QGrade|index|integer|A grade based on QGrade system which was developed to rate the quality of coffee from 0-100|
|Independent|Water filter age|months|integer|Months passed since replacement of the water filter|
|Independent|Desired coffee-based drink|-|string|The name of the desired coffee-based drink|
|**Independent**|**Taste rating**|**index**|**integer**|**A rating given by the user for the extracted coffee**|

## Model
