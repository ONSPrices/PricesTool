# CPI tool
Tool to visualise experimental CPI indices created from web scraped data.

To access the tool visit https://onsprices.github.io/PricesTool/index.html (Development version)

TO DO:

- [ ]  Labels following mouse
- [x]  Bigger Title 
- [x]  Zoom Option
- [x]  Add all five indexes: LCPI, Daily Chain, Unit Price Index, GEKSJ, CLIP 
- [x]  Option to turn ON/OFF indexes   
- [x]  Level structure 
- [x]  Define data structure 
- [x]  Dynamic update date 


### Data structure
```
.
+-- Monthly
  +-- Level 0
    +-- Overwiew
  +-- Level 1
    +-- Food
    +-- Alcoholic
+-- Weekly
  +-- Level 0
    +-- Overwiew
  +-- Level 1
    +-- Food
    +-- Alcoholic
```

### Data point
```
{"category":"010000Food & Non-Alcoholic Beverages", "index":"Index0", "value":100,"date":"01/06/14"}
```


