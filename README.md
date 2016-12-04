# MySQLimportedSqoop_HDFSFiles

# Sqoop is used to import the Mysql database to HDFS, for that I have used below sqoop import command.

""
sqoop import --connect jdbc:mysql://192.168.2.61/employees --username hadoop1 --password password --table departments --m 1

""

Here 
1.First I have imported all Mysql tables using sqoop to HDFS
2.Then from HDFS I have copied  it to my loacl and Uploaded here.


