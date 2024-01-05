- It must be emphasized that data-modelling need special attention simply because it is the foundation of Power BI "Reports".
- A good data model helps us to get the right results. 
- It also facilitates performance tuning, managing the storage constraints & row level security, authoring DAX, and in fact everything !
- What is a data model? A data model defines all tables and HOW they are related to each other. 
- There are two major data modelling styles. The simplest one is the "Star Schema" model consists of one or more FACT tables surrounded by any number of DIMENSIONAL tables. Note that Fact table contaons measures or items (of a business process) that can be aggregated, while a Dimension table contains descriptive attributes defining how a fact should roll up.


  
  ![Star Schema](https://learn.microsoft.com/en-us/power-bi/guidance/media/star-schema/star-schema-example2.png)



- The Snowflake Schema is the extension of the Star Schema that adds additional dimensions (representing hierarchies).
