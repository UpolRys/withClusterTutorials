command:
* sbt package //this will create a jar file that we need to submit while rnning our job on the cluster, it will locate it to target/scala-versin folder
* spark-submit --class com.spark.MovieSimilarities ./target/scala-2.11/withClusterTutorials_2.11-0.1.jar