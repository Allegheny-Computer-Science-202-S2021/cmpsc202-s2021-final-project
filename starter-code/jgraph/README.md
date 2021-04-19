# Running the program
Linux/Mac:
-----------------------------------------------------------
Type in the following commands on your terminal. Make sure you are inside the jgraph folder. 
./compile.sh
./run.sh


To compile from root directory:
```shell
javac -d "bin" -cp "bin:jar/*" src/com/web/*.java
```
To run from root directory:
```shell
java -cp "bin:jar/*" com.web.TreeVisualizer
```