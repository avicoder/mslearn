---
    layout: post
    title: Work with DataFrames columns in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-dataframes-columns-azure-databricks/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-dataframes-columns-azure-databricks.svg">
####  1. Which command orders by a column in descending order?


<i class='far fa-square'></i> &nbsp;&nbsp;df.orderBy("requests desc")

<i class='far fa-square'></i> &nbsp;&nbsp;df.orderBy("requests").desc()

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;df.orderBy(col("requests").desc())
<br />
<br />
<br />

####  2. Which command specifies a column value in a DataFrame's filter? Specifically, filter by a productType column where the value is equal to book?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;df.filter(col("productType") == "book")

<i class='far fa-square'></i> &nbsp;&nbsp;df.filter("productType = 'book'")

<i class='far fa-square'></i> &nbsp;&nbsp;df.col("productType").filter("book")
<br />
<br />
<br />

####  3. When using the Column Class, which command filters based on the end of a column value? For example, a column named verb and filtered by words ending with "ing".


<i class='far fa-square'></i> &nbsp;&nbsp;df.filter().col("verb").like("\%ing")

<i class='far fa-square'></i> &nbsp;&nbsp;df.filter("verb like '\%ing'")

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;df.filter(col("verb").endswith("ing"))
<br />
<br />
<br />
