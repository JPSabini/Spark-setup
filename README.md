# Spark-setup
Cloudera VM Spark-set up

### Install IPython

From the top left menu, Open a terminal: Applications => System Tools => Terminal

Type:
```
sudo easy_install ipython==1.2.1
```
Hit enter, administrator password is cloudera.

###Launch pyspark with IPython

Every time you need to open the pyspark shell, open a terminal and type:
```
PYSPARK_DRIVER_PYTHON=ipython pyspark
```
Hit enter, after the startup logs, you should see the pyspark console:

Check version

To make sure that PySpark started correctly, print out the version by typing in the PySpark IPython terminal:
```
sc.version
```

Verify that the output is:
```
u'1.3.0'
```

### Spark -csv Installation link:

http://spark-packages.org/package/databricks/spark-csv

type in terminal

```
PYSPARK_DRIVER_PYTHON=ipython pyspark --packages com.databricks:spark-csv_2.10:1.3.0
```
