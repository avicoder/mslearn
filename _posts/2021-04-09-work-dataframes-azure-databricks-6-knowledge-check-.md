---
    layout: post
    title: Work with DataFrames in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-dataframes-azure-databricks/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-dataframes-azure-databricks.svg">
####  1. Which DataFrame method do you use to create a temporary view?


<i class='far fa-square'></i> &nbsp;&nbsp;createTempView()

<i class='far fa-square'></i> &nbsp;&nbsp;createTempViewDF()

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;createOrReplaceTempView()
<br />
<br />
<br />

####  2. How do you create a DataFrame object?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Introduce a variable name and equate it to something like myDataFrameDF =

<i class='far fa-square'></i> &nbsp;&nbsp;Use the createDataFrame() function

<i class='far fa-square'></i> &nbsp;&nbsp;Use the DF.create() syntax
<br />
<br />
<br />

####  3. How do you cache data into the memory of the local executor for instant access?


<i class='far fa-square'></i> &nbsp;&nbsp;.save().inMemory()

<i class='far fa-square'></i> &nbsp;&nbsp;.inMemory().save()

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;.cache()
<br />
<br />
<br />

####  4. What is the Python syntax for defining a DataFrame in Spark from an existing Parquet file in DBFS?


<i class='far fa-square'></i> &nbsp;&nbsp;IPGeocodeDF = parquet.read("dbfs:/mnt/training/ip-geocode.parquet")

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;IPGeocodeDF = spark.read.parquet("dbfs:/mnt/training/ip-geocode.parquet")

<i class='far fa-square'></i> &nbsp;&nbsp;IPGeocodeDF = spark.parquet.read("dbfs:/mnt/training/ip-geocode.parquet")
<br />
<br />
<br />
