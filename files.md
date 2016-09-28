   1. Open a terminal on your local machine, SSH into the bigfoot
1. ```
  ssh <user>@bigfoot.ccs.miami.edu
  ```

2.  Move a file to your home directory on bigfoot

1. ```
  scp -r <filename> <user>@dev3.ccs.miami.edu:.
  ```


1.  Create a directory

2. ```
  hdfs dfs -mkdir <name of the directory>
  ```

3. Put files into the directory
4. ```
  hdfs dfs -put <local file name> <name of the directory you created> 
  ```


1.  List the contents of the directory

  ```
  hdfs dfs -ls
  ```

2. Space utilized by file
  ```
  hdfs dfs -du <folder/ file name>
  ```

3. Get file from hdfs to your loacal directory
  ```
  hdfs dfs -get <path of yoyr hdfs file>
  ```

4. 





