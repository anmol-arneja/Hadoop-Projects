In this problem, we identify each day as either a hot day or cold day.
The input data for solving this problem is Weather_dataset.txt
We have done it both using Map Reduce and by using pig script
Both the map reduce code and pig scripts can be found inside src folder.

Instructions for running this program

You can run pig script directly inside the grunt shell

For map reduce program WeatherData.java, you need to create a jar file and  add the external jars given in lib folder
The input file patent should be in hdfs and can be copied to hdfs using following commad:
hdfs dfs -copyFromLocal '[Local location where you have saved file Weather_dataset.txt]'
Run the jar giving following command
cd /[Location where your jar is stored]
hadoop jar [your created jar file] [input data in file stored in hdfs] [output file where output is to be stored]
