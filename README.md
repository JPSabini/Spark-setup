# Spark-setup
Cloudera VM Spark-set up

### Install IPython

From the top left menu, Open a terminal: Applications => System Tools => Terminal

Type:

sudo easy_install ipython==1.2.1

Hit enter, administrator password is cloudera.

###Launch pyspark with IPython

Every time you need to open the pyspark shell, open a terminal and type:

PYSPARK_DRIVER_PYTHON=ipython pyspark

<p style='color:red'>This is some red text.</p>
