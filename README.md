# BigData-Bio21
## Setup instructions
! Please `git pull` from this repository each time you begin to 
develop anything !
### Use Maven 
Based on IntelliJ IDEA, maven usage can simplify the 
development of mapreduce jobs without Hadoop environments. 
see instructions [here](https://www.polarxiong.com/archives/Hadoop-Intellij%E7%BB%93%E5%90%88Maven%E6%9C%AC%E5%9C%B0%E8%BF%90%E8%A1%8C%E5%92%8C%E8%B0%83%E8%AF%95MapReduce%E7%A8%8B%E5%BA%8F-%E6%97%A0%E9%9C%80%E6%90%AD%E8%BD%BDHadoop%E5%92%8CHDFS%E7%8E%AF%E5%A2%83.html).
The main branch is the template for development with maven.
### Use Hadoop locally
See instructions on the slides.
## Project organization
Please use git to switch between branches. The `main` branch is the template for all. Each task should be be assigned to 
a specific branch and each member is supposed to folk the task branch and develop on their own branch. A merge request 
is expected after finishing. The flow is as below:
```
-- main --------------------------------------
        |-- task2 -------------------   
        |           |-- dev1 --|^  |^       
        |           |-- dev2 ------|        
        |-- task3 -------------------
```