---
    layout: post
    title: Work with user-defined functions 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-with-user-defined-functions/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-with-user-defined-functions.svg">
####  1. What is the correct syntax to register the UDF, f, as my_function in SQL namespace?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;spark.udf.register("my_function", f)

<i class='far fa-square'></i> &nbsp;&nbsp;spark.register_udf("my_function", f)

<i class='far fa-square'></i> &nbsp;&nbsp;spark.udf.register(f, "my_function")
<br />
<br />
<br />

####  2. What is the correct syntax for specifying the return type for an UDF?


<i class='far fa-square'></i> &nbsp;&nbsp;my_udf = udf(f, "LongType()")

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;my_udf = udf(f, "long")

<i class='far fa-square'></i> &nbsp;&nbsp;my_udf = udf(f, return_type = "long")
<br />
<br />
<br />

####  3. What is one of the drawbacks of UDFs?


<i class='far fa-square'></i> &nbsp;&nbsp;UDFs cannot operate on DataFrames.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The function has to be serialized and sent out to the executors.

<i class='far fa-square'></i> &nbsp;&nbsp;UDFs can only operate one row at a time.
<br />
<br />
<br />
