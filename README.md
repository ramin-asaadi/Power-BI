# **_Data-Modelling needs special attention !_**
- Data modelling is the foundation of Power BI "Reports".
- A good data model helps us to get the right results ! 
- A good data model also facilitates _performance tuning, managing the storage constraints & row level security, authoring DAX, and in fact everything !_
  
- **What is a data model?** A data model defines all tables & **HOW** they are related to each other. 
- There are two major data modelling styles: **Star Schema** & **Snowflake Schema**.
- **Star Schema** is the simplest one consists of one or more **Fact** tables surrounded by any number of **Dimensional** tables. Note that while **Fact** table contains **measures** or **items** (of a business process) that can be aggregated, a **Dimension** table contains **descriptive attributes** defining how a fact should roll up.


  
  ![Star Schema](https://learn.microsoft.com/en-us/power-bi/guidance/media/star-schema/star-schema-example2.png)



- The Snowflake Schema is the extension of the Star Schema that adds additional dimensions (representing hierarchies).
