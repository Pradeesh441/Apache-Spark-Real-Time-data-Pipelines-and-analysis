Instructions
-------------------------
Option - 1
IBM Datascience Experience

Select Data and Analytics Option
Once done start with Data Science Experience 

--------------------------
Option - 2
Install Apache Spark and perform following tasks

Python –Python 2.7 version installed in  local machine. 
$Python –version
$Sudo apt-get update

Pip – Installed with below command. 
$sudo apt install python-pip 
$ sudo apt-get update 
$ sudo pip -version

Ipython  has been Installed under home directory and also set the environment variable.
$sudo apt-get -y install ipython ipython-notebook

Jupyter is installed with the following command and the environment variable is also set.
$sudo –H pip install jupyter
To start - $jupyter notebook 

Spark has been downloaded from apache spark homepage and saved to local path
$pyspark - To start pyspark  in jupyter notebook
export JAVA_HOME=/home/Pradeesh/jdk1.8.0_121 
export SPARK_HOME=/home/Pradeesh/spark-2.1.0-bin-hadoop2.7 export SCALA_HOME=/home/Pradeesh/scala-2.12.1

export PATH=$PATH:$SCALA_HOME/bin:$SPARK_HOME/bin:$JAVA_HOME/bin
export PYSPARK_DRIVER_PYTHON=jupyter 
export PYSPARK_DRIVER_PYTHON_OPTS=notebook
