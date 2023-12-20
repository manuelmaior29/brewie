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

### Features
|Name|MU|Data Type|Description|
|---|---|---|---|
|Grind size setting|index|integer|   |
|Grind size setting burr|index|integer|   |
|Extraction time|seconds|integer|   |
|Shot multiplier|index|integer|   |
|Coffee origin|-|string|   |
|Coffee time since roast|days|integer|   |
|Coffee processing type|-|string|   |
|Coffee QGrade|index|integer|   |
|Coffee quantity|grams|float|   |
