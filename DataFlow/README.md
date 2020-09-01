
https://beam.apache.org/get-started/quickstart-java/ 
https://cloud.google.com/dataflow/docs/quickstarts/quickstart-java-maven  

##  生成项目

```
mvn archetype:generate \
      -DarchetypeGroupId=org.apache.beam \
      -DarchetypeArtifactId=beam-sdks-java-maven-archetypes-examples \
      -DarchetypeVersion=2.23.0 \
      -DgroupId=org.example \
      -DartifactId=word-count-beam \
      -Dversion="0.1" \
      -Dpackage=org.apache.beam.examples \
      -DinteractiveMode=false
```
##  maven方式运行

```
mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.WordCount \
     -Dexec.args="--inputFile=pom.xml --output=counts" -Pdirect-runner
```




#  Apache Beam编程框架介绍   
https://wenku.baidu.com/view/177a29272a160b4e767f5acfa1c7aa00b52a9dc1.html   


#  下一代实时流数据处理平台介绍 
https://wenku.baidu.com/view/bff9f6c7cf2f0066f5335a8102d276a20129604a.html?fr=search-3   

# # Apache Beam 实战指南之基础入门
https://www.infoq.cn/article/apache-beam-in-practice


#  # Apache Beam 架构原理及应用实践
https://www.infoq.cn/article/aLy182Jgm6MTiTg7NL0r


#  # Apache Beam研究报告

https://www.jianshu.com/p/5899b6d632cf   


# Airflow tutorial
https://github.com/tuanavu/airflow-tutorial





