### Install Apache Spark on MacOS via conda

1. Install the Anaconda distribution
2. Install OpenJDK 11 <br>
`conda install -c anaconda openjdk`
3. Install PySpark
`conda install -c conda-forge pyspark`

Now we should be able to run pyspark in a notebook with anaconda.

If your notebook is not installed via anaconda, try to install FindSpark to let notebook find pyspark: <br>
`conda install -c conda-forge findspark`