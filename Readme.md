# Azure Databricks Hands-on (Tutorials)

Follow each instructions on notebook below.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of Pyspark and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (requires ML runtime)
6. [Horovod Runner on Databricks Runtime for ML](https://tsmatz.github.io/azure-databricks-exercise/exercise06-horovod.html) (requires ML runtime)
7. [Structured Streaming (Basic)](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure EventHub or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Delta Lake](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [Work with MLFlow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html) (requires ML runtime)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)

## Before you start

- Create Azure Databricks resource in [Microsoft Azure](https://portal.azure.com/), and launch workspace. See details from instructor or from the [Quickstart]().

- Create a computing cluster on Databricks workspace. (Select "Compute" in Workspace UI.)<br>
Databricks **Runtime Version 10.2 ML or above** is recommended for running this tutorial.

- Download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) and import into your workspace.
    - Select "Workspace" in Workspace UI.
    - Go to user folder.
    - Click your e-mail (the arrow in the right side) and select "import" command to import HandsOn.dbc.
- Open the imported notebook and attach your cluster in the notebook. (Select cluster on top of notebook.)

> Note : You cannot use Azure Trial (Free) subscription, because of limited vCPU quota. Please promote to Pay-As-You-Go when you use trial subscription. (The credit will be reserved even when you transit to Pay-As-You-Go.)

## Additional resources for further exploration
- Azure has extensive [documentation online](https://docs.microsoft.com/en-us/azure/databricks/).
- Databricks has even more training materials listed in this [Guide](https://files.training.databricks.com/lms/docebo/course-catalog.pdf).  The Azure material is specifically relevant.  While they say this is free customer training, it only takes a free registration to become a "customer".
- Books (most of which are available on Oreilly online):
    - [Azure Databricks Cookbook](https://learning.oreilly.com/library/view/azure-databricks-cookbook/9781789809718/) This one is better than many Manning Cookbooks and is pretty helpful.
    
    - [Advanced Analytics with PySpark](https://learning.oreilly.com/library/view/advanced-analytics-with/9781098103644/) This is an update of one of my favorite books on Spark, made accessible to Python. This previous version focused on Scala.

    - [Azure Databricks](https://learning.oreilly.com/playlists/b4f4bb9f-8cb8-4f2d-8732-771d5a1d9146/) This playlist has extensive references.
    
    - [Delta Lake: The Definitive Guide](https://learning.oreilly.com/library/view/delta-lake-the/9781098104580/) I find this one to be a bit much, but it sure is definative.

-Videos:
    -[Debugging Apache Spark](https://learning.oreilly.com/videos/debugging-apache-spark/9781492039174/) This one is a bit older for Spark, but the author, *Holden Karau*, is a great longtime advocate of PySpark and open source big data contributor.  She is a great speaker, and does coding livestreaming on Youtube and Twitch. Look out for her dog Timbit, who makes occasional appearances.  

    -[Building Your First ETL Pipeline Using Azure Databricks](https://app.pluralsight.com/library/courses/building-etl-pipeline-microsoft-azure-databricks/table-of-contents) For a review of some of the material covered last week.

    -[Predictive Analytics Using Apache Spark MLlib on Databricks](https://app.pluralsight.com/library/courses/predictive-analytics-apache-spark-mlib-databricks) Janani Ravi is one of my favorite instructors on Pluaralsight discussing Spark and ML.  This course is part of this learning path: https://app.pluralsight.com/paths/skill/apache-spark-on-databricks





Modified by *Ed Fine @Afinepoint*  
Links to code provided to keep up to date.
Original code by *Tsuyoshi Matsuzaki @ Microsoft*
