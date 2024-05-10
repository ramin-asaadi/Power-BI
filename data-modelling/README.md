# Dataset

Above I have a **.csv file**; A flat table including **19 fields & 675,368 rows of data**:

- ProductID
- Date
- CustomerID
- CampaignID
- Units
- Product
- Category
- Segment
- ManufacturerID
- Manufacturer
- Unit Cost
- Unit Price
- ZipCode
- Email Name
- City
- State
- Region
- District
- Country

## Conceptual Model
In order to model the data, I first distingush between facts and dimensions to build a [conceptual model](https://powerbi.microsoft.com/en-us/blog/the-conceptual-data-model-and-limits/). 

- FactSales
- DimDate
- DimProduct
- DimCategory
- DimCustomer


![ConceptualModel](https://github.com/ramin-asaadi/data-modelling-in-power-bi/assets/155740766/6cab1dbc-001c-4c14-b31e-b518e10ccfd6)


## Cleaning the Data
Having the conceptual model, we now need to clean the data.  

