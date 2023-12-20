# brewie

## Table of Contents

- [Overview](#overview)
  
## Overview

After getting a coffee-making machine there are a lot of situations in which the extracted coffee does not end up to our expectations. Some of us enjoy a balanced taste with slight bitterness while others prefer to drink a slightly acid coffee. Considering this, the idea of developing an ML-based system, that could aid the extraction process, specifically providing tips for adjusting parameters from _grind size_, _coffee quantity_ and _extraction time_ up to _coffee origin_, in order to achieve the desired coffee taste.
<br />
![alt text](images/coffee-icon.jpg)
<a href="https://www.vecteezy.com/free-vector/cappuccino">Cappuccino Vectors by Vecteezy</a>

## Data

Given that the application might be rather coffee machine dependent, the data used for implementing an ML-based, extraction settings optimization system, would be defined on the _Sage's the Barista Express™_ machine (since this one is close at hand for me).

### Variables
|Type|Name|MU|Data Type|Description|
|---|---|---|---|---|
|Output|Grind size setting|index|integer|The main adjustment value made on the grinder|
|Output|Grind size setting burr|index|integer|The adjustment value made on the grinder burr|
|Output|Extraction time|seconds|integer|The time passed from the first drop of coffee until the water is stopped|
|Output|Extraction quantity|grams|float|The quantity of water passed through coffee|
|Output|Coffee quantity|grams|float|The quantity of coffee used for extraction|
|Input|Coffee origin|-|string|The region from which the coffee was harvested|
|Input|Coffee time since roast|days|integer|The time passed since the coffee was roasted|
|Input|Coffee processing type|-|string|The method used for processing the coffee beans after harvesting|
|Input|Coffee QGrade|index|integer|A grading system which grades the quality of coffee from 0-100|
