# Spark-API-Guide

This projects contains Databricks notebooks explaining about the various APIs avaiable in Spark scala API in Spark 2.x. Tried to add little explanation before each API to understand the concept behind it and then actual code and how to use it with an explanation

The project contains mutliple notebooks, with each notebooks explaing a specific concepts like Spark Session, Datasets, DataframeReader etc. Please go over the below table to look for specfic topics and then click on the link to open the notebook

S.No. | Topic | Contents 
------|-------|----------
1|[Spark Session](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/1198152224612140/1911168149879216/latest.html) | This notebook contains the basic functions available with spark API like configurations, reading data and metadata functions.
2|[Dataframe Vs Dataset](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/3138174879831521/1911168149879216/latest.html)| This notebook compares the two structured APIs i.e Dataframes & Datasets and try explain the difference between these two programatically. 
3|[Dataframe Vs Dataset](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/1829240461540036/1911168149879216/latest.html)| This notebook explains the standard API to access the metadata like temp table, registered udfs on SQL context or permanent metadata like Hive meta store or HCatalog.
4|[Basic DataSet Functions](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/3138174879831538/1911168149879216/latest.html)| This notebook explains some of the basic methods available in Dataset API i.e schema , explain, view creations, etc.,
5|[Datasets -Typed Transformation Functions](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/3814699026941541/1911168149879216/latest.html)| This notebook explains some of the tranformation functions map, filter, flatmap, randomsplit, repartition, groupByKey, sample,etc
6|[Basic SQL Functions](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/3984117177573328/1911168149879216/latest.html)| This notebook explains basic sql functions like select, filter, where, orderBy, sort, limit, NA , stat,etc.,
7|[Aggregate Functions](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/4043338700243415/1911168149879216/latest.html)| This notebook covers all the aggregate functions available in Spark i.e groupBy, window, pivot, rolup,cube.
8|[Join Functions](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/2357259023612622/1911168149879216/latest.html)| This notebook covers all the join functions available in Spark i.e Inner,Outer, LeftOuter,RightOuter, LeftSemi, LeftAnti,Cross & Neutral Joins
9|[Datasources](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/3429922385246449/1911168149879216/latest.html)| This notebook covers reading and writing data from/to various datasources i.e csv, json, orc,parquet,avro, hive table, sql table, xml files.
10|[DatasetActions](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6907863442366616/3984117177573389/1911168149879216/latest.html)| This notebook covers all the available actions in Dataset
