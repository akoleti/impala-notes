###     Open a terminal on your local machine, SSH into the bigfoot

1. 1. ```
    ssh <user>@bigfoot.ccs.miami.edu
    ```


  ### Move a file to your home directory on bigfoot

2. ```
  scp -r <filename> <user>@dev3.ccs.miami.edu:.
  ```

  ### Create a directory

3. ```
  hdfs dfs -mkdir <name of the directory>
  ```

  ### Put files into the directory

4. ```
  hdfs dfs -put <local file name> <name of the directory you created> 
  ```

  ### List the contents of the directory

  ```
  hdfs dfs -ls
  ```

  ### Space utilized by file

  ```
  hdfs dfs -du <folder/ file name>
  ```

  ### Get file from hdfs to your loacal directory

  ```
  hdfs dfs -get <path of yoyr hdfs file>
  ```









# 

1. 

